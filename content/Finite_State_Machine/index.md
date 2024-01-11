+++
title = 'Finite State Machine'
date = 2023-10-23T16:44:33-08:00
draft = false
description = "Finite State Machine (FSM)"
image = "/images/cpp_icon.webp"
imageBig = "/images/cpp_icon.webp"
categories = ["cpp"]
authors = ["Crux Cook"]
avatar = "/images/avatar.webp"
projSrc = "https://github.com/cruxcook/fsm"
+++

![screenshot](images/fsm_screenshot.webp)

> Developed in [GCC](https://gcc.gnu.org/)

## Contents

-   [Project Configuration](#1-project-configuration)
-   [Features](#2-features)
-   [Usage](#3-usage)

---

### 1. Project Configuration

-   GCC: 14.0.0

### 2. Features

Navigates between states (`Menu`, `About`, `Exit`).

### 3. Usage

To compile and build the project:

```shell
$ make
```

After that, we can run the project:

```shell
$ make run

# or 

$ ./FSM
```

To clean or rebuild the project:

```shell
$ make clean; make

# or

$ make rebuild
```