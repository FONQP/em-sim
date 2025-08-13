# em-sim
### A performant electromagnetic simulation Python package, written in Rust.

(Heavily inspired by [Meep](https://meep.readthedocs.io/en/latest/))

## Installation
To add as a dependency in your Python project:
```bash
uv add em-sim
```

## Usage
```python
import em_sim as em

cube = em.Block(
    center=(0, 0, 0),
    size=(1, 1, 1),
    material=em.Material.Si
)
```

***
2025 | Prasanna Paithankar
