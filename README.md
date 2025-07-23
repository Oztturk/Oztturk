```ts
// github.com/Oztturk

type Developer = {
  name: string;
  languages: string[];
  frontend: string[];
  backend: string[];
  learning: string[];
  contact: {
    discord: string;
    email: string;
  };
};

const Oztturk: Developer = {
  name: "Oztturk",
  languages: ["TypeScript", "JavaScript", "Node.js", "Luau", "C#", "Python", "C++"],
  frontend: ["React", "TailwindCSS", "shadcn/ui"],
  backend: ["Express.js", "Gin (Go)"],
  learning: ["C++", "Gin", "Low-level optimization"],
  contact: {
    discord: "yuzuf",
    email: "oztturk@proton.me"
  }
};

export default Oztturk;
```
