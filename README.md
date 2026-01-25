# MW Lab - Millyweb Development

**Systems, services, and MCP for building modern conversational SaaS**

🌐 [millyweb.com](https://millyweb.com) | 💼 [LinkedIn](https://linkedin.com/company/millyweb)

---

## 🛠️ Active Projects

### MCP Infrastructure
| Repository | Description | Status |
|------------|-------------|--------|
| **[mcp-tool-flow](https://github.com/rdmilly/mcp-tool-flow)** | Complete MCP Tool Flow Architecture - OAuth Gateway, Semantic Tool Filter, Name Bridge, Context Forge | ✅ Production |
| **[claude-operating-instructions](https://github.com/rdmilly/claude-operating-instructions)** | Modular instruction files for Claude AI sessions | ✅ Active |

### Social Media & Automation
| Repository | Description | Status |
|------------|-------------|--------|
| **[stitch](https://github.com/rdmilly/stitch)** | AI-powered social media content generation & scheduling | 🔄 Building |

### Infrastructure Tools
| Repository | Description | Status |
|------------|-------------|--------|
| **[brain-path-projects](https://github.com/rdmilly/brain-path-projects)** | AWL project management system | ✅ Active |
| **[project-tracker](https://github.com/rdmilly/project-tracker)** | Public project tracker - building in public | ✅ Active |

---

## 🌟 Current Architecture

### VPS Infrastructure
```
VPS1 (72.60.31.69) - Gateway
├── Traefik (reverse proxy, SSL termination)
├── Coolify (deployment platform)
└── Edge routing

VPS2 (72.60.225.81) - Workloads  
├── PostgreSQL / Redis
├── Context Forge (MCP aggregation)
├── 18 MCP Server gateways
├── Prometheus / Grafana / Loki
└── 220+ tools available

Connected via: WireGuard VPN
Backup: BTRFS cross-server replication
```

### MCP Tool Flow
```
Claude.ai → OAuth Gateway → Tool Filter → Name Bridge → Context Forge → MCPJungle
                                         |
                                  95% token reduction
                                  (40,000 → 800 tokens)
```

---

## 📈 Key Metrics
- **MCP Tools Available:** 220+ (from 18 gateways)
- **Token Optimization:** 95% reduction
- **Infrastructure Cost:** ~$40/month VPS
- **Uptime Target:** 99.9%

---

## 📚 Related Brands

- **[RevenueFirst.AI](https://revenuefirst.ai)** - AI sales automation consulting for service businesses
- **[Signal](https://github.com/rdmilly/signal)** - Personal knowledge library

---

*Building in public from Portland, Oregon*
*Last updated: January 25, 2026*