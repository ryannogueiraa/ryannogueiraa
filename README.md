<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,100:0066FF&height=120&section=header"/>

<h1 align="center">Hi there, I'm Ryan Nogueira 👋</h1>
<h4 align="center">Assistente de Tecnologia | Software Developer | AI Integrations</h4>

<p align="center">
  <a href="https://www.linkedin.com/in/ryan-nogueira-631867347/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="28">
  </a>
  <a href="mailto:ryannogueira125@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28">
  </a>
</p>

<br>

## 👨‍💻 `ryan_nogueira.ts`

```typescript
import { Developer, ProblemSolver } from 'software-engineering';

class Ryan extends Developer implements ProblemSolver {
    name = "Ryan Nogueira";
    role = "Assistente de Tecnologia @ Grupo Costa Norte";
    
    stack = {
        backEnd: ["C#", ".NET Core", "Java", "Python", "REST APIs"],
        frontEnd: ["TypeScript", "JavaScript", "Angular", "React", "Next.js"],
        databases: ["SQL Server", "MySQL", "PostgreSQL", "MongoDB", "Supabase"],
        ai: ["Prompt Engineering", "Machine Learning", "LLMs API", "Python Automation"]
    };

    async executeDailyRoutine(): Promise<void> {
        while (this.awake) {
            await this.writeCode();
            await this.integrateAI();
            await this.refactor();
        }
    }

    getMission(): string {
        return "Construir sistemas escaláveis unindo engenharia tradicional e Inteligência Artificial, resolvendo problemas reais do negócio.";
    }
}
