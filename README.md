<h1 align="center">template-meta</h1>

<div align="center">

Template for templates 🧶

[![Lint](https://github.com/radio-aktywne/template-meta/actions/workflows/lint.yaml/badge.svg)](https://github.com/radio-aktywne/template-meta/actions/workflows/lint.yaml)
[![Test](https://github.com/radio-aktywne/template-meta/actions/workflows/test.yaml/badge.svg)](https://github.com/radio-aktywne/template-meta/actions/workflows/test.yaml)

</div>

---

## 💡 About

This repository contains a [`copier`](https://copier.readthedocs.io) template
that can be used to create other templates for `radio-aktywne` projects.

## 📜 Usage

To create a new template in the current directory,
make sure you have [`copier`](https://copier.readthedocs.io) installed and run:

```sh
copier gh:radio-aktywne/template-meta .
```

## 🚀 Features

- fully reproducible development environments with
  [`Dev Containers`](https://code.visualstudio.com/docs/remote/containers)
  and [`Nix`](https://nixos.org)
- automatic environment activation with [`direnv`](https://direnv.net)
- running tasks with [`Task`](https://taskfile.dev)
- formatting and linting with [`Trunk`](https://trunk.io)
- continuous integration with [`GitHub Actions`](https://github.com/features/actions)

## 💻 Contributing and Development

Read more about how to contribute and develop the project
[here](https://github.com/radio-aktywne/template-meta/blob/main/CONTRIBUTING.md).
