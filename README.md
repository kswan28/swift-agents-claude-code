# swift-agents-claude-code
A series of customized SwiftUI agents for Claude Code ✨💎

# 🎯 Swift & iOS Claude Agents - Elite SwiftUI Specialists for Claude Code

> **Transform Claude Code into your personal iOS development team with a set of hyper-specialized SwiftUI agents.** Expert assistance for animations, design consistency, onboarding flows, code management, and data persistence.

[![GitHub stars](https://img.shields.io/github/kswan28/swift-agents-claude-code?style=social)](https://github.com/kswan28/swift-agents-claude-code)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Compatible](https://img.shields.io/badge/Claude%20Code-Compatible-blue)](https://claude.ai)
[![Agents: 5](https://img.shields.io/badge/Agents-5-green)](https://github.com/kswan28/swift-agents-claude-code)

## 🎯 What are Swift & iOS Claude Agents?

Swift & iOS Claude Agents is a curated collection of AI-powered specialists designed to enhance Claude Code with deep SwiftUI and iOS development expertise. Whether you're building delightful animations, ensuring design consistency, creating onboarding flows, managing code changes, or implementing data persistence, these agents provide expert-level assistance following Apple's design guidelines.

### Key Features:
- **5 Specialized SwiftUI Agents**: Covering animation, design, onboarding, rollbacks, and data persistence
- **Apple Design Guidelines**: Each agent follows iOS Human Interface Guidelines
- **Performance Optimized**: All agents use Claude Sonnet 4 for optimal performance
- **Zero Configuration**: Works instantly with Claude Code
- **Production Ready**: Battle-tested patterns for iOS apps

## The SwiftUI Power-Up You've Been Waiting For

Imagine having instant access to 5 world-class iOS specialists, each a master of their SwiftUI craft. No more generic advice. No more non-iOS patterns. Just deep, iOS-focused expertise on demand.

## ⚡ Lightning Setup - Install Swift Agents in Seconds

### Method 1: Using Claude Code (Recommended)
```bash
# In Claude Code, use the agents command
/agents

# Then manually create each agent and copy content from the GitHub files
```

### Method 2: Clone and Copy
```bash
# Clone the repository
git clone https://github.com/kswan28/swift-agents-claude-code.git

# Create agents directory and copy agent files
mkdir -p ~/.claude/agents
cp swift-agents-claude-code/*.md ~/.claude/agents/

# Clean up
rm -rf swift-agents-claude-code

# That's it. Your SwiftUI game just leveled up.
```

### Method 3: Direct Download (All Agents)
```bash
# Create agents directory
mkdir -p ~/.claude/agents
cd ~/.claude/agents

# Download all agent files
curl -O https://raw.githubusercontent.com/kswan28/swift-agents-claude-code/main/back-to-december.md
curl -O https://raw.githubusercontent.com/kswan28/swift-agents-claude-code/main/long-live.md
curl -O https://raw.githubusercontent.com/kswan28/swift-agents-claude-code/main/shake-it-off.md
curl -O https://raw.githubusercontent.com/kswan28/swift-agents-claude-code/main/style.md
curl -O https://raw.githubusercontent.com/kswan28/swift-agents-claude-code/main/welcome-to-new-york.md
```

## 🎯 How to Use Swift Agents with Claude Code

### Step 1: Install the Agents
Follow one of the installation methods above. This creates the structure:
```
~/.claude/
└── agents/
    ├── back-to-december.md
    ├── long-live.md
    ├── shake-it-off.md
    ├── style.md
    └── welcome-to-new-york.md
```

### Step 2: Start Claude Code
```bash
claude code
```

### Step 3: Use Agents in Your SwiftUI Projects

To use an agent, type `/agents` and select the appropriate specialist:

**Example 1: Adding Animations**
```
You: I want to add smooth animations to my SwiftUI button interactions
You: /agents
[Select shake-it-off from the list]

shake-it-off: I'll analyze your SwiftUI Views for animation opportunities.
[Analyzes your View structure]
- Found tap interactions that need animation feedback
- Button state changes could benefit from spring animations  
- Navigation transitions could be smoother

Here's how to enhance your interactions...
```

**Example 2: Design Consistency Audit**
```
You: My app's typography and spacing feels inconsistent across screens
You: /agents
[Select style from the list]

style: I'll audit your entire app's design system.
[Performs comprehensive style analysis]
- Found 12 different font sizes (recommend 6 standardized sizes)
- Inconsistent button padding across 8 components
- Missing semantic color usage in 15 locations

Here's your detailed consistency report...
```

**Example 3: Building Onboarding**
```
You: I need to create an onboarding flow for my fitness app
You: /agents
[Select welcome-to-new-york from the list]

welcome-to-new-york: I'll create your onboarding experience.

Let me ask a few questions first:
- How many onboarding screens do you need?
- What permissions does your fitness app require?
- Should users be able to skip the flow?

Based on your answers, I'll create a polished onboarding flow...
```

## Meet Your SwiftUI Specialists

### 🎨 shake-it-off - The Animation Virtuoso
When your UI needs that perfect touch of delight:
- Analyzes SwiftUI Views for animation opportunities
- Adds native, performance-optimized animations
- Follows Apple's motion guidelines
- Creates smooth 60fps experiences

**Perfect for:** Button feedback, state transitions, loading animations, micro-interactions

### 🎯 style - The Design System Guardian  
When your app's visual consistency needs attention:
- Audits typography, spacing, and color usage
- Identifies design system inconsistencies
- Provides actionable improvement reports
- Ensures professional, cohesive interfaces

**Perfect for:** Design system audits, typography cleanup, component standardization

### 🚀 welcome-to-new-york - The Onboarding Architect
When first impressions matter:
- Creates multi-screen onboarding flows
- Handles iOS permission requests properly
- Builds feature highlight screens
- Ensures smooth app introduction

**Perfect for:** User onboarding, permission flows, feature showcases, app introductions

### ⏪ back-to-december - The Code Time Machine
When you need to undo recent changes safely:
- Reviews Claude Code conversation history
- Identifies recent code modifications
- Provides safe rollback strategies
- Preserves important work while fixing problems

**Perfect for:** Code rollbacks, session management, change recovery, git workflows

### 💾 long-live - The Data Persistence Master
When your app needs robust data storage:
- Designs SwiftData models and relationships  
- Sets up persistent storage solutions
- Implements CRUD operations properly
- Ensures data survives app launches

**Perfect for:** SwiftData setup, data modeling, persistence patterns, storage optimization

## 🔥 Real Session Examples

### Scenario: "My SwiftUI app feels boring and static"
```bash
$ claude code

You: My SwiftUI app works but feels lifeless. Can you help make it more engaging?
You: /agents
[Select shake-it-off]

shake-it-off: I'll add delightful animations to your SwiftUI app.

Share your View code and I'll identify key interaction points that would benefit from animation:
- Button tap responses
- State change transitions  
- Content loading states
- Navigation animations

Let's make your app feel alive and responsive...

[Proceeds to analyze code and add smooth, native SwiftUI animations]
```

### Scenario: "My app's design is inconsistent"
```bash
You: Different screens in my app look like they were designed by different people
You: /agents
[Select style]

style: I'll audit your entire app's design system.

Please share your SwiftUI files and I'll analyze:
- Font sizes and typography hierarchy
- Spacing and padding consistency
- Color usage patterns
- Component styling alignment

📊 **Design Consistency Report:**

**Typography Issues Found:**
- 14 different font sizes used (recommend 6 standardized)
- Missing Dynamic Type support in 8 components
- Inconsistent heading hierarchy across screens

**Component Inconsistencies:**
- Button padding varies from 8pt to 24pt
- Card corner radius inconsistent (8pt, 12pt, 16pt)
- List item spacing not standardized

**Recommendations:**
1. Create standardized font scale
2. Implement consistent spacing tokens
3. Standardize component designs

[Provides detailed fix recommendations with code examples]
```

### Scenario: "Need to add user onboarding"
```bash
You: My app needs a smooth onboarding experience for new users
You: /agents
[Select welcome-to-new-york]

welcome-to-new-york: I'll create your onboarding flow.

First, let me understand your requirements:
- How many onboarding screens do you envision?
- What iOS permissions does your app need? (notifications, location, camera, etc.)
- What are the key features users should understand?
- Should users be able to skip the onboarding?

Based on your answers:

✅ **Onboarding Architecture:**
- Welcome screen with app value proposition
- Feature highlights (3 screens)  
- Permission requests (notifications, location)
- Completion flow with smooth main app transition

[Builds comprehensive SwiftUI onboarding with proper navigation and permissions]
```

## Why This Changes Your SwiftUI Development

### 🎯 iOS-Native Excellence
Each agent specializes in SwiftUI and iOS patterns. No generic web advice.

### 🧠 Apple Guidelines Compliance  
All agents follow Apple's Human Interface Guidelines and design principles.

### ⚡ Instant SwiftUI Expertise
No ramp-up time. Each agent comes pre-loaded with iOS development experience.

### 💰 Optimized Performance
All agents use Claude Sonnet 4 for the perfect balance of capability and cost.

## 📋 Complete Swift Agent Roster

### 🎨 Animation & Interaction Specialists
`shake-it-off` - Adds delightful, performance-optimized SwiftUI animations to Views

### 🎯 Design & Consistency Experts  
`style` - Audits and fixes typography, spacing, and visual inconsistencies

### 🚀 User Experience Architects
`welcome-to-new-york` - Creates polished onboarding flows with permission handling

### ⏪ Development Tools & Workflow
`back-to-december` - Safely manages code rollbacks and session history

### 💾 Data & Persistence Masters
`long-live` - Implements robust SwiftData solutions for app data storage

## Start Building Better SwiftUI Apps Now

```bash
# Example: Improve app animations
"My SwiftUI buttons feel unresponsive"
/agents → Select shake-it-off (adds button animations)
/agents → Select style (ensures consistent interaction patterns)
```

```bash
# Example: Launch preparation  
"My app is ready to ship but needs polish"
/agents → Select style (design audit)
/agents → Select welcome-to-new-york (onboarding flow)  
/agents → Select long-live (data persistence check)
```

## 🌟 Why Choose Swift & iOS Claude Agents?

### For iOS Developers
- **SwiftUI Focused**: Every agent understands SwiftUI patterns and best practices
- **Apple Guidelines**: All recommendations follow iOS Human Interface Guidelines
- **Performance Optimized**: Solutions designed for smooth 60fps iOS experiences

### For Teams
- **Consistent iOS Standards**: All agents follow the same iOS development principles
- **Knowledge Sharing**: Team members get equal access to SwiftUI expertise
- **Faster Reviews**: Automated consistency checks and pattern validation

### For App Studios
- **Professional Quality**: Enterprise-grade iOS development patterns
- **Client Ready**: Production-ready code that impresses clients
- **Rapid Iteration**: Build, polish, and ship iOS apps faster

## 📈 Performance & Quality

Each agent is optimized for:
- **Native Performance**: Solutions designed for iOS performance characteristics
- **Accessibility**: Built-in support for VoiceOver and Dynamic Type
- **Best Practices**: Industry-standard iOS development patterns

## 🔍 Keywords for Discovery

SwiftUI Claude agents, iOS development AI, Claude Code SwiftUI, SwiftUI animations, iOS design consistency, SwiftUI onboarding, SwiftData persistence, iOS code management, SwiftUI best practices, Apple design guidelines, iOS app development AI, SwiftUI performance optimization

---

## 👨‍💻 About the Creator

Built with passion for iOS developers who create apps users love. This collection represents deep SwiftUI expertise and Apple design guideline knowledge, distilled into 5 powerful AI specialists.

## 📜 License

MIT License - Use these agents freely in your iOS projects!

## 🤝 Contributing  

Found ways to improve an agent? Have ideas for new SwiftUI specialists? Contributions are welcome! Please check our [contribution guidelines](CONTRIBUTING.md).

## ⭐ Support the Project

If Swift & iOS Claude Agents helps you build better iOS apps, please star the repository!

[![Star on GitHub](https://img.shields.io/github/stars/yourusername/claude-code-agents?style=social)](https://github.com/kswan28/swift-agents-claude-code)

---

**Swift & iOS Claude Agents** - *Transform Claude Code into Your Personal iOS Development Team*

*🔗 [GitHub](https://github.com/kswan28/swift-agents-claude-code) | 💬 [Issues](https://github.com/kswan28/swift-agents-claude-code/issues) | 📱 [iOS Development](https://developer.apple.com)*