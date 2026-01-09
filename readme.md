# Injury Process Flowchart

```mermaid
flowchart TD
  A([Injury occurs]) --> B[Immediate response: first aid / call 911 if needed<br/><b>R:</b> Supervisor + Injured Employee]
  B --> C[Initial report to Supervisor<br/><b>R:</b> Injured Employee<br/><b>A:</b> Supervisor]
  C --> D[Supervisor reports incident to EHS + HR<br/><b>R/A:</b> Supervisor]
  D --> E[EHS incident intake + fact collection<br/><b>A/R:</b> EHS]
  D --> F[HR claim admin intake (WC kickoff)<br/><b>A/R:</b> HR]

**Important:** The line that says **```mermaid** is what tells GitHub “draw this as a diagram.” :contentReference[oaicite:3]{index=3}

---

### 5) Save it (Commit)
Scroll down to the bottom:
1. In “Commit message” type something like: `Add injury process flowchart`
2. Click **Commit new file**

---

### 6) See the picture
Go back to your repo main page. The README should show, and the Mermaid block should render as a diagram. GitHub supports Mermaid diagrams in Markdown using fenced code blocks. :contentReference[oaicite:4]{index=4}

---

## If you only see code (instead of a diagram)
This usually means the fence is wrong. The opening fence must be exactly:

```text
```mermaid
