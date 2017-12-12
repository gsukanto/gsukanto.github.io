# Gregory Sukanto personal website

This is a personal website from Gregory Sukanto. Contains anything that he find it's fun to have.

- [Project Structure](#project-structure)
- [Coding Guidelines](#coding-guidelines)


### Project Structure

This project is structured as:

```
.
├── README.md
└── cv
    ├── gregory_sukanto.html
    ├── gregory_sukanto.pdf
    ├── index.html
    └── resume.json
```

### Coding Guidelines

- **Requirement**: Read [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- **Pull Requests**: Make sure the code works. Assume the reviewer is dumb.
- **Business Logic**: If writing a fair amount of business logic that should be unit tested, you should write the code in a modular way that can easily be unit tested.
- **KISS**: always Keep It Simple Stupid
- **Functional Programming**: High order function, atomic (or Singleton),  single responsibility principle, pure function, encapsulation, immutable
- **Avoid class**: I hate class.
- **100x30**: 100 length maximum, with 30 line maximum (should be able to read from my Atom with 14 pt font and normal theme without scrolling)
