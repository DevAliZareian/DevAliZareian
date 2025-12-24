<p align="center">
 <img src="https://readme-typing-svg.herokuapp.com/?lines=Welcome+to+my+GitHub+Profile!&center=true&width=360&height=30">
</p>
<p align="center">Portfolio: https://devalizareian.ir</p>

```typescript
class DevAliZareian { 
  name: Ali;
  age: number;
  role: string;
  TOOLS: Record<string, string[]>;
  INTERESTS: string[];
  
  constructor() {
    this.name = "Fardin";
    this.age = 19;
    this.role = "Front-End Developer";
    
    this.TOOLS = {
      "Frontend": ["NextJS" ,"React", "React Router", "TypeScript", "JavaScript (ES6+)"],
      "StateManagement": ["React Query", "Context API", "Redux Toolkit"],
      "Performance": ["Memoization", "Lazy Loading", "Suspense", "Optimization Techniques"],
      "APIs": ["GraphQL", "REST APIs"],
      "Testing": ["React Testing Library"],
      "Styling": ["Tailwind CSS", "Styled Components"],
      "BuildTools": ["Vite", "Webpack"],
      "Platforms": ["Web"],
      "Version Control": ["Git, GitHub"]
    };
    
    this.INTERESTS = [
      "Web Development",
      "UI/UX Design",
      "Performance Optimization",
      "Open Source Contributions"
    ];
  }
  
  use(tool: keyof typeof this.TOOLS): string[] | undefined {
    /** Use a specific toolset from the stack */
    return this.TOOLS[tool];
  }
  
  work(): void {
    /** Keep coding and improving */
    while (true) {
      console.log("Building cool projects with React...");
    }
  }
  
  get height(): number {
    /** Fun Fact */
    return 174; // cm
  }
  
  toString(): string {
    return `${this.name}, a ${this.age}-year-old passionate ${this.role}.`;
  }
}

const ali = new DevAliZareian();
console.log(ali.toString());

```
