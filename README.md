<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:5B21B6,100:0891B2&height=230&section=header&text=saviourmk&fontSize=78&fontColor=FFFFFF&fontAlignY=36&desc=Go%20%C2%B7%20Rust%20%C2%B7%20Python%20%C2%B7%20Solidity%20%C2%B7%20Full%20Stack&descSize=20&descAlignY=58&animation=fadeIn" width="100%" alt="saviourmk" />
</p>

<p align="center">
  <a href="https://github.com/saviourmk">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=8B5CF6&center=true&vCenter=true&width=640&lines=Full+Stack+%26+Blockchain+Engineer;Concurrent+backends+in+Go+and+Rust;Python+for+data%2C+AI+and+automation;Secure%2C+gas-efficient+Solidity+contracts;From+idea+to+production%2C+end+to+end" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/saviourmk?tab=followers"><img src="https://img.shields.io/github/followers/saviourmk?label=Followers&style=for-the-badge&color=8B5CF6&logo=github&logoColor=white" alt="Followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=saviourmk&label=Profile%20views&color=0891B2&style=for-the-badge" alt="Profile views" />
  <img src="https://img.shields.io/badge/Open%20to-Freelance%20%26%20Contracts-22C55E?style=for-the-badge" alt="Open to freelance and contracts" />
</p>

<br />

## 👋 About me

I'm a **full stack engineer** who builds fast, reliable software across the whole stack: concurrent backends in **Go** and **Rust**, data and automation in **Python**, secure smart contracts in **Solidity**, and polished web apps in **TypeScript** and **React**.

I like owning a product end to end, from the database schema and the API to the contract on chain and the pixels on screen.

- 🔭 Building production backends, Web3 dApps and AI-powered tools
- 💬 Ask me about Go concurrency, Rust performance, smart contract security and system design
- 🤝 Open to freelance projects, contract work and open source collaboration
- ⚡ Fun fact: I pick the language for the problem, not the other way around

```go
package main

import "fmt"

type Engineer struct {
    Handle    string
    Role      string
    Languages []string
    Frontend  []string
    Backend   []string
    Web3      []string
    DevOps    []string
}

func (e Engineer) Motto() string {
    return "Build it right, make it fast, keep it secure."
}

func main() {
    me := Engineer{
        Handle:    "saviourmk",
        Role:      "Full Stack & Blockchain Engineer",
        Languages: []string{"Go", "Rust", "Python", "Solidity", "TypeScript"},
        Frontend:  []string{"React", "Next.js", "Tailwind CSS"},
        Backend:   []string{"Gin", "Actix", "FastAPI", "Node.js", "gRPC", "GraphQL"},
        Web3:      []string{"Ethereum", "EVM L2s", "Foundry", "Hardhat", "OpenZeppelin"},
        DevOps:    []string{"Docker", "Kubernetes", "AWS", "GitHub Actions"},
    }
    fmt.Println(me.Motto())
}
```

<details>
<summary><b>🦀 🐍 ⛓️ Same profile in Rust, Python and Solidity</b></summary>
<br />

```rust
struct Engineer {
    handle: &'static str,
    languages: &'static [&'static str],
}

fn main() {
    let me = Engineer {
        handle: "saviourmk",
        languages: &["Go", "Rust", "Python", "Solidity"],
    };
    println!("{} ships in {}", me.handle, me.languages.join(", "));
}
```

```python
from dataclasses import dataclass, field


@dataclass
class Engineer:
    handle: str = "saviourmk"
    languages: list[str] = field(
        default_factory=lambda: ["Go", "Rust", "Python", "Solidity"]
    )

    def motto(self) -> str:
        return "Build it right, make it fast, keep it secure."


print(Engineer().motto())
```

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.24;

contract Saviourmk {
    string public constant ROLE = "Full Stack & Blockchain Engineer";
    string[4] public languages = ["Go", "Rust", "Python", "Solidity"];

    event Hired(address indexed client);

    function hire() external {
        emit Hired(msg.sender);
    }
}
```

</details>

<br />

## 🛠️ What I build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ Backend & Systems</h3>
      <sub><b>Go · Rust</b></sub>
      <ul>
        <li>High-throughput REST and gRPC APIs</li>
        <li>Microservices and event-driven pipelines</li>
        <li>Concurrency done right: goroutines, channels, async Rust</li>
        <li>Low-latency services, CLI tools and WebAssembly</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⛓️ Smart Contracts & Web3</h3>
      <sub><b>Solidity · EVM</b></sub>
      <ul>
        <li>ERC-20, ERC-721 and ERC-1155 tokens</li>
        <li>DeFi: staking, vaults, swaps and governance</li>
        <li>Upgradeable proxies and gas optimization</li>
        <li>Fuzz-tested with Foundry, security-first design</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🐍 Python, Data & AI</h3>
      <sub><b>Python · FastAPI · Django</b></sub>
      <ul>
        <li>Fast, typed APIs with FastAPI and Django</li>
        <li>Automation, bots and scrapers</li>
        <li>Data pipelines and analytics</li>
        <li>LLM integrations and AI agents</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ Full Stack Products</h3>
      <sub><b>TypeScript · React · Next.js</b></sub>
      <ul>
        <li>Responsive web apps and dApp frontends</li>
        <li>Auth, payments, dashboards and admin panels</li>
        <li>PostgreSQL and Redis data layers</li>
        <li>CI/CD, Docker and cloud deployments</li>
      </ul>
    </td>
  </tr>
</table>

<br />

## 🧰 Tech stack

<table align="center">
  <tr>
    <td align="center" width="140"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=go,rust,py,solidity,ts,js,bash&theme=dark" height="44" alt="Languages" /></td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,html,css&theme=dark" height="44" alt="Frontend" /></td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,fastapi,django,flask,actix,graphql&theme=dark" height="44" alt="Backend" /></td>
  </tr>
  <tr>
    <td align="center"><b>Web3</b></td>
    <td>
      <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white" alt="Ethereum" />
      <img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white" alt="Solidity" />
      <img src="https://img.shields.io/badge/Foundry-1C1C1C?style=for-the-badge" alt="Foundry" />
      <img src="https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge" alt="Hardhat" />
      <img src="https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white" alt="OpenZeppelin" />
      <img src="https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white" alt="Chainlink" />
      <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethers&logoColor=white" alt="Ethers.js" />
      <img src="https://img.shields.io/badge/wagmi-1C1B1B?style=for-the-badge&logo=wagmi&logoColor=white" alt="wagmi" />
      <img src="https://img.shields.io/badge/Polygon-7B3FE4?style=for-the-badge&logo=polygon&logoColor=white" alt="Polygon" />
      <img src="https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white" alt="Solana" />
      <img src="https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white" alt="IPFS" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase,prisma,kafka,rabbitmq&theme=dark" height="44" alt="Databases and messaging" /></td>
  </tr>
  <tr>
    <td align="center"><b>DevOps & Cloud</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,cloudflare,vercel,terraform,nginx,linux,githubactions,prometheus,grafana&theme=dark" height="44" alt="DevOps and cloud" /></td>
  </tr>
</table>

<br />

## 🧭 How I work

- 🧱 **Clean architecture** · readable code, clear boundaries, documented decisions
- 🧪 **Tested by default** · unit, integration and fuzz tests before anything ships
- 🔐 **Security first** · audit-ready contracts, least-privilege infrastructure
- 🚀 **Ship and iterate** · CI/CD, observability and fast feedback loops
- 💬 **Clear communication** · regular updates and honest estimates

<!--
## 🚀 Featured projects
Replace REPO_ONE and REPO_TWO with your public repo names, then remove this comment wrapper.

<p align="center">
  <a href="https://github.com/saviourmk/REPO_ONE">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=saviourmk&repo=REPO_ONE&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=C9D1D9" alt="REPO_ONE" />
  </a>
  <a href="https://github.com/saviourmk/REPO_TWO">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=saviourmk&repo=REPO_TWO&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=C9D1D9" alt="REPO_TWO" />
  </a>
</p>
-->

<br />

## 📊 GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=saviourmk&show_icons=true&rank_icon=github&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=C9D1D9&ring_color=8B5CF6" />
    <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=saviourmk&show_icons=true&rank_icon=github&hide_border=true&bg_color=FFFFFF&title_color=6D28D9&icon_color=0891B2&text_color=334155&ring_color=7C3AED" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=saviourmk&layout=compact&langs_count=8&hide=html,css&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" />
    <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saviourmk&layout=compact&langs_count=8&hide=html,css&hide_border=true&bg_color=FFFFFF&title_color=6D28D9&text_color=334155" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=saviourmk&hide_border=true&background=0D1117&ring=8B5CF6&fire=22D3EE&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=8B949E&stroke=30363D" />
    <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=saviourmk&hide_border=true&background=FFFFFF&ring=7C3AED&fire=0891B2&currStreakNum=0F172A&sideNums=0F172A&currStreakLabel=6D28D9&sideLabels=6D28D9&dates=64748B&stroke=E2E8F0" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=saviourmk&hide_border=true&area=true&bg_color=0D1117&color=C9D1D9&line=8B5CF6&point=22D3EE&area_color=8B5CF6&title_color=A78BFA&custom_title=Contribution%20activity" />
    <img width="100%" alt="Contribution activity" src="https://github-readme-activity-graph.vercel.app/graph?username=saviourmk&hide_border=true&area=true&bg_color=FFFFFF&color=334155&line=7C3AED&point=0891B2&area_color=7C3AED&title_color=6D28D9&custom_title=Contribution%20activity" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/saviourmk/saviourmk/output/github-snake-dark.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/saviourmk/saviourmk/output/github-snake.svg" />
  </picture>
</p>

<br />

## 🤝 Let's connect

<p align="center">
  <a href="https://github.com/saviourmk"><img src="https://img.shields.io/badge/GitHub-saviourmk-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <!-- Add your contacts here (remove the comment marks around the ones you use):
  <a href="https://discord.com/users/YOUR_DISCORD_ID"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/YOUR_X_HANDLE"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://t.me/YOUR_TELEGRAM"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  -->
</p>

<p align="center">
  <i>Have an idea, a product or a contract that needs building? Let's make it real.</i>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,50:5B21B6,100:0F172A&height=120&section=footer" width="100%" alt="" />
</p>
