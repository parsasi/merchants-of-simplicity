# Simplicity

> It's hard to sell simple, because simple looks easy, and who wants to pay for that?

-- DHH

---

## Let's play a game - Supabase

> Build in a weekend, Scale to --------

-- Supabase

---

## Let's play a game - Supabase

> Build in a weekend, Scale to millions

-- Supabase

---

## Let's play a game - Render

> Build, deploy, and scale your apps with unparalleled ease – from your first user to your ---------

-- Render

---

## Let's play a game - Render

> Build, deploy, and scale your apps with unparalleled ease – from your first user to your billionth

-- Render

---

## Let's play a game - PlanetScale

> The world's fastest and most ----- cloud databases

-- PlanetScale

---

## Let's play a game - PlanetScale

> The world's fastest and most scalable cloud databases

-- PlanetScale

---

## Parsa Safavi

- Senior Developer @ ORX Travel

- Creator of Metrists

---

## Code execution

```go
package main

import "fmt"

func main() {
  fmt.Println("Execute code directly inside the slides")
}
```

You can execute code inside your slides by pressing `<C-e>`,
the output of your command will be displayed at the end of the current slide.

---

## Pre-process slides

You can add a code block with three tildes (`~`) and write a command to run _before_ displaying
the slides, the text inside the code block will be passed as `stdin` to the command
and the code block will be replaced with the `stdout` of the command.

```
~~~graph-easy --as=boxart
[ A ] - to -> [ B ]
~~~
```

The above will be pre-processed to look like:

┌───┐ to ┌───┐
│ A │ ────> │ B │
└───┘ └───┘

For security reasons, you must pass a file that has execution permissions
for the slides to be pre-processed. You can use `chmod` to add these permissions.

```bash
chmod +x file.md
```
