# Cambo
Hello, Today Let me show you how i made a web development framework in pypi.
## Installation
```bash
pip install Cambo
```

## Usage
```python
import Cambo

cambo = Cambo.Cambo()

@cambo.page('/')
def main():
    return 'Welcome to Cambo!'

@cambo.page('/about')
def about():
    return 'This is a simple framework called Cambo.'

if __name__ == "__main__":
    cambo.run()
```

## Output
```bash
Running on http://127.0.0.1:8000
```
