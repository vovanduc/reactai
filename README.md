<p align="center">
  An open source project that can generate React Components.
</p>

## Workflow

```mermaid
graph TD
    A[User] -->|Access| B[Web Application]
    B --> C{Authentication}
    C -->|Logged in| D[Dashboard]
    C -->|Not logged in| E[Login/Register]
    
    D --> F[Features]
    F -->|1| G[Code Editor]
    F -->|2| H[Share Code]
    F -->|3| I[Template Examples]
    
    G -->|Save| J[(Database)]
    H -->|Generate| K[Share Link]
    I -->|Load| L[Template Code]
    
    subgraph Backend
    J
    end
    
    subgraph Frontend
    G
    H
    I
    end
```


## Tech stack

- [Claude AI](https://www.anthropic.com/) Claude AI Models
- [Sandpack](https://sandpack.codesandbox.io/) for the code sandbox
- Next.js app router with Tailwind
- Prisma Postgress Database
- CodeSandbox/Sandpack (Code editor)
- Tailwind CSS (Styling)

## Examples Demo generated using ReactAI

- [Popup Modal](https://reactai.vasarai.net/share/_ajy9)

![popup modal](examples/gifs/popup-modal-reactai.gif)

- [Newsletter Form](https://reactai.vasarai.net/share/qfhed)

![newsletter form](examples/gifs/newsletter-form-reactai.gif)

- [Todo App](https://reactai.vasarai.net/share/nLQ1G)

![todo app](examples/gifs/todo-app-reactai.gif)

- [Counter App](https://reactai.vasarai.net/share/EGzfh)

![counter app](examples/gifs/counter-app-reactai.gif)

- [Calculator App](https://reactai.vasarai.net/share/SNSb3)

![calculator app](examples/gifs/calculator-app-reactai.gif)

- [Image Generator](https://reactai.vasarai.net/share/gldbD)

![image generator](examples/gifs/image-generator-reactai.gif)

- [Chat App](https://reactai.vasarai.net/share/450ym)

![chat app](examples/gifs/chat-app-reactai.gif)