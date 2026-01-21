# test_data.json
[
  {
    "code_snippet": "query = f'SELECT * FROM users WHERE id = {user_id}'\ndb.execute(query)",
    "language": "Python",
    "expected_label": "Vulnerable",
    "issue_type": "SQL Injection"
  },
  {
    "code_snippet": "def add_numbers(a, b):\n    return a + b",
    "language": "Python",
    "expected_label": "Safe",
    "issue_type": "None"
  }
]