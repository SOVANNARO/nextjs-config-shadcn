## 💡 Config Shadcn with Next JS

### ✅ Run the `init` command:

```
pnpm dlx shadcn@latest init
```

```
? which style would you like to use? > Default
? which color would you like use as base color? > Slate
? Would you like to use CSS variables for colors? > yes
```

### ✍️ Noted: 🚧 If have this message while installing:

```
It looks like you are using React 19.
Some packages may fail to install due to peer dependency issues in npm (see https://ui.shadcn.com/react-19).
```

👉 Solution Next.js 15 + React 19: https://ui.shadcn.com/docs/react-19

### ✅ Add Testing with Button use CLI

```
pnpm dlx shadcn@latest add button
```

### ✅ Testing with Button is Completed

```tsx
import { Button } from "@/components/ui/button";

export default function Home() {
  return (
    <div className="flex justify-center items-center h-screen">
      <Button>Click me</Button>
    </div>
  );
}
```

👉 Reference: https://ui.shadcn.com/docs
