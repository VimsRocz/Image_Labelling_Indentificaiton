# Contributing to Image Labelling Identification

Thanks for your interest in contributing 🎉

## How to Contribute

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Open a pull request

## Development Setup

```bash
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
```

## Commit Guidelines

Use clear commit messages, for example:

- `feat: add CLI option for confidence threshold`
- `fix: improve distance estimation for low-light frames`
- `docs: update setup instructions`

## Pull Request Checklist

- [ ] Code runs locally
- [ ] Documentation updated when behavior changes
- [ ] No sensitive keys or credentials committed
- [ ] Large model/data artifacts are not committed

## Code Style

- Prefer readable, well-named variables
- Add comments where non-obvious math is used
- Keep functions focused and testable
