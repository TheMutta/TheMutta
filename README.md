# Hello, world!
## Introductions
Hi, I'm Jess!

I'm a professional Rust/C/C++ developer,
working both in the operating system and embedded spaces,
with some game dev by the side.

I'm 19 and I come from Venice, Italy.

## Projects
I am currently doing a big refactor of this account, so not all the projects are currently available. However, expect to find:
 - Kernels
 - Data structures 
 - Parsers
 - Libraries
 - And so much more

If specifically you want access to some source code while the refactor is going on, please ask away! I am always available.

# Source code down here
```
struct programmer_t {
  const char *introduction;
  char *profession;
  unsigned int age;
  char *location;
};

int main() {
  printf("Hello, world!");

  struct programmer_t jessica = {
    .introduction = "Hi, I'm Jess!",
    .profession = "I'm a professional Rust/C/C++ developer, \
                   working both in the operating system and embedded spaces, \
                   with some game dev by the side.",
    .age = 19,
    .location = "Venice, Italy",
  };

  enter_my_lab(&jessica);
  return 0;
}

void enter_my_lab(programmer_t *programmer) {
}
```

}

```
