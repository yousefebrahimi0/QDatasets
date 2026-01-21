# Contributing to QDatasets 🤝

Thank you for considering contributing to QDatasets! We welcome contributions from the quantum computing community.

## Ways to Contribute

### 1. Submit a Dataset

Have a quantum ML dataset to share? We'd love to include it!

**Requirements:**
- Dataset must be publicly accessible
- Include proper licensing information
- Provide metadata (format, size, use case)
- Include usage example (optional but recommended)

**Submission Process:**
1. Fork this repository
2. Add your dataset metadata to `datasets/` directory
3. Follow our metadata schema (see below)
4. Submit a pull request
5. Our team will review and merge

**Metadata Schema Example:**
```json
{
  "name": "Your Dataset Name",
  "category": "chemistry|optimization|classification|simulation",
  "description": "Brief description",
  "size_gb": 2.4,
  "num_samples": 134000,
  "qubit_range": "4-12",
  "frameworks": ["qiskit", "pennylane"],
  "license": "CC BY 4.0",
  "download_url": "https://...",
  "paper_url": "https://arxiv.org/...",
  "citation": "BibTeX format"
}
```

### 2. Report Issues

Found a bug or broken link?
- Open an [issue](https://github.com/yousefebrahimi0/qdatasets/issues)
- Include: what happened, what you expected, steps to reproduce

### 3. Improve Documentation

Help make quantum ML more accessible:
- Fix typos or unclear explanations
- Add tutorials or examples
- Translate documentation

### 4. Add Usage Examples

Show how to use datasets with:
- Qiskit, PennyLane, Cirq, TensorFlow Quantum
- Different quantum algorithms (VQE, QAOA, QNN)
- Add examples to `examples/` directory

### 5. Code Contributions

Want to contribute code for the backend or API?
- Check [open issues](https://github.com/yousefebrahimi0/qdatasets/issues)
- Comment on the issue you want to work on
- Fork, code, test, submit PR

---

## Code of Conduct

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions.

---

## Pull Request Process

1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feature/your-feature`)
3. **Commit** your changes (`git commit -m 'Add some feature'`)
4. **Push** to the branch (`git push origin feature/your-feature`)
5. **Open** a Pull Request

**PR Guidelines:**
- Clear description of what you changed and why
- Reference related issues
- Include tests if adding new functionality
- Update documentation if needed

---

## Quality Standards

- **Code:** Follow PEP 8 for Python code
- **Datasets:** Must have proper licenses and citations
- **Documentation:** Clear, concise, beginner-friendly
- **Examples:** Must be tested and working

---

## Recognition

All contributors will be acknowledged in our README and on our website!

---

## Questions?

Open a [Discussion](https://github.com/yousefebrahimi0/qdatasets/discussions) or email me!

Thank you for helping build the future of quantum ML!
