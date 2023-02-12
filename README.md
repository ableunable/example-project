# example-project
i made this long ago as an example to teach someone to use github. now it's a playground for experimenting like with what's below:

-----------

it's a graph! not the best but it's a bit complicated to make 'em. check the `<>` above ([here](https://github.com/ableunable/example-project/blob/main/README.md)) to see the source!   
<details><summary>disclaimer</summary>i can't guarantee it'll render the same on your screen but the arrows should always point to what i coded them to point to</details>

```mermaid
flowchart LR
  subgraph Get PC
    subgraph The default
      direction BT
      a("1. get computer") -----> b("2. comes with windows")
    end
    subgraph What do?
      direction TB
      subgraph MAC
        c(buy a mac)
        d(???)
        d x--x c
      end
      b -- "(if you got monies)" --- c
      subgraph LINUX
        direction TB
        e(install linux)
        f(install another distro)
        x(do i like it?)
        g(install arch linux)
        b -- "free!" --> e
        e --> f
        f ---- x
        x -- No --> f
        f ---> g
        h(screw it up beyond repair)
        g ---> h ---> g
      end
    end
    MAC & LINUX -- "i need a new computer" --> a
    want("Want to make your own graphs?") -- "(click the next node)" --> Link([here's how!])
    click Link "https://mermaid.js.org/#/" "Mermaid!"
  end
  linkStyle 2 color:skyblue,stroke:#0af,stroke-width:4px,font-weight:bold;
  linkStyle 3 stroke:#0a1,stroke-width:4px,color:lime;
```
