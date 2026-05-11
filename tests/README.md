# Testing Structure

This directory contains the test suites for the project, covering both backend and frontend components.

## Directory Layout

- `backend_smoke_test.py`: A minimal smoke test for the backend.
- `FRONTEND_TEST_PLAN.md`: Documentation outlining the strategy and framework for frontend testing.

## Running Tests

### Backend
To run backend tests, use `unittest`:
```bash
python3 -m unittest discover tests -p '*_test.py'
```

### Frontend
Frontend tests are currently being planned. Refer to `FRONTEND_TEST_PLAN.md` for more details.
