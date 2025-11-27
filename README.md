<p align="center"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/d0c03f5a-af31-462e-84cb-5bac735b0f18">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/e616d532-bf05-4ea1-a266-8e7ddeed3553">
  <img height="60" src="https://github.com/user-attachments/assets/d0c03f5a-af31-462e-84cb-5bac735b0f18" />
</picture></p>

<p align="center">
  <img src="https://img.shields.io/badge/license-PPL--Mesa--2025-black?v=1&labelColor=%23303030&color=%23c0c0c0&text=PPL-Mesa-2025" />
  <img src="https://img.shields.io/github/repo-size/prospect-lab/ComplexUI?v=1&labelColor=%23303030&color=%23c0c0c0" />
  <img src="https://img.shields.io/github/issues/prospect-lab/ComplexUI?v=1&labelColor=%23303030&color=%23c0c0c0" />
  <img src="https://img.shields.io/github/issues-pr/prospect-lab/ComplexUI?v=1&labelColor=%23303030&color=%23c0c0c0" />
</p>

ComplexUI is an open-source version of vComplex Infrastructure. It's a web design and
layout management framework where you can develop apps without touching CSS. Yet it's
similar to other competitors, it's main purpose is to be as simple and advanced
as possible, allowing you to manage style rules over HTML classes and attributes.

> [!WARNING]
> This project is currently facing a rewrite. It is highly unstable and it has some missing parts, in it's current state it'll not be 100% compatible with vComplex.

<h3>Building</h3>
For building procedures, we use <a href="https://github.com/neotesk/truct"><b><img width="12" height="12" alt="logo" src="https://github.com/user-attachments/assets/1a8052d1-924c-4799-9037-8a7c6ac5fc68" />Truct</b></a>.
We've written several workflows for development.

#### Build everything
```
truct do
```
This command will build everything into the `build/` directory, containing the CSS and JS artifacts.

#### Building CSS only
```
truct do css
```
This command will build SCSS files into the `build/` directory.

## Motives and Copyright
This project was originally closed source. We've decided to make it open-source and free
(as in freedom) so everyone can use, modify and redistribute this project.

Contributors of the original project belongs to given copyright holders in [COPYRIGHT.md](./COPYRIGHT.md)
