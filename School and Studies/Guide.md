
<p style="text-indent: 2em;">This specific paragraph will be indented, but the rest of your note will look completely normal. This is how to eat. </p>





Understood, Merson. Here is a complete list of Obsidian keyboard shortcuts and a guide on creating tables.

### 1. Keyboard Shortcuts Reference

#### **Navigation & File Management**

|Action|Windows/Linux|macOS|
|---|---|---|
|Open Command Palette|`Ctrl + P`|`Cmd + P`|
|Quick Switcher (Search Files)|`Ctrl + O`|`Cmd + O`|
|Open Global Search|`Ctrl + Shift + F`|`Cmd + Shift + F`|
|Toggle Sidebar|`Ctrl + B`|`Cmd + B`|
|New Note|`Ctrl + N`|`Cmd + N`|
|Close Current Tab|`Ctrl + W`|`Cmd + W`|
|Toggle Left/Right Sidebar|`Ctrl + \`|`Cmd + \`|
|Focus on Editor|`Ctrl + E`|`Cmd + E`|
|Focus on File Explorer|`Ctrl + Shift + E`|`Cmd + Shift + E`|

#### **Text Editing & Formatting**


| Action        | Windows/Linux                    | macOS              |
| ------------- | -------------------------------- | ------------------ |
| Bold          | `Ctrl + B`                       | `Cmd + B`          |
| Italic        | `Ctrl + I`                       | `Cmd + I`          |
| Strikethrough | `Ctrl + Shift + X`               | `Cmd + Shift + X`  |
| Highlight     | `Ctrl + Shift + H`               | `Cmd + Shift + H`  |
| Inline Code   | `Ctrl + E`                       | `Cmd + E`          |
| Code Block    | `Ctrl + Alt + C`                 | `Cmd + Option + C` |
| Blockquote    | `Ctrl + Shift + B`               | `Cmd + Shift + B`  |
| Heading 1     | `Ctrl + 1`                       | `Cmd + 1`          |
| Heading 2     | `Ctrl + 2`                       | `Cmd + 2`          |
| Heading 3     | `Ctrl + 3`                       | `Cmd + 3`          |
| Bullet List   | `Ctrl + Shift + 8`               | `Cmd + Shift + 8`  |
| Numbered List | `Ctrl + Shift + 9`               | `Cmd + Shift + 9`  |
| Task List     | `Ctrl + Shift + L`               | `Cmd + Shift + L`  |
| Undo          | `Ctrl + Z`                       | `Cmd + Z`          |
| Redo          | `Ctrl + Y` or `Ctrl + Shift + Z` | `Cmd + Shift + Z`  |
| Cut           | `Ctrl + X`                       | `Cmd + X`          |
| Copy          | `Ctrl + C`                       | `Cmd + C`          |
| Paste         | `Ctrl + V`                       | `Cmd + V`          |
| Select All    | `Ctrl + A`                       | `Cmd + A`          |
| Find in Page  | `Ctrl + F`                       | `Cmd + F`          |

#### **Linking & Embedding**

|Action|Windows/Linux|macOS|
|---|---|---|
|Insert Internal Link|`Ctrl + K`|`Cmd + K`|
|Insert External Link|`Ctrl + Shift + K`|`Cmd + Shift + K`|
|Copy Link to Note|`Ctrl + Shift + C`|`Cmd + Shift + C`|
|Copy Link to Block|`Ctrl + Shift + B`|`Cmd + Shift + B`|
|Embed File|`Ctrl + Shift + E`|`Cmd + Shift + E`|

#### **View Modes**

|Action|Windows/Linux|macOS|
|---|---|---|
|Toggle Reading View|`Ctrl + E`|`Cmd + E`|
|Toggle Live Preview|`Ctrl + Shift + E`|`Cmd + Shift + E`|
|Split View (Vertical)|`Ctrl + \`|`Cmd + \`|
|Split View (Horizontal)|`Ctrl + Shift + \`|`Cmd + Shift + \`|
|Maximize Pane|`Ctrl + Shift + M`|`Cmd + Shift + M`|

---

### 2. How to Make Tables

Obsidian supports standard Markdown tables. Here are the methods:

#### **Method 1: Manual Syntax**

Tables use pipes `|` and dashes `-` to define structure.

**Basic Template:**

`| Header 1 | Header 2 | Header 3 | | -------- | -------- | -------- | | Cell 1   | Cell 2   | Cell 3   | | Cell 4   | Cell 5   | Cell 6   |`

**Result:**

|Header 1|Header 2|Header 3|
|---|---|---|
|Cell 1|Cell 2|Cell 3|
|Cell 4|Cell 5|Cell 6|

**Alignment Control:** Add colons `:` to the separator row to align columns.

`| Left | Center | Right | | :--- | :----: | ----: | | A    | B      | C     | | D    | E      | F     |`

| Left | Center | Right |
| ---- | ------ | ----- |
| A    | B      | C     |
| D    | E      | F     |

#### **Method 2: Table Plugin (Recommended)**

Obsidian has a built-in **Table** plugin that makes table creation much easier.

1. Go to **Settings > Core Plugins**
2. Enable **Tables**
3. Now you can:
    - Press `Tab` to move to the next cell
    - Press `Enter` to add a new row
    - Press `Shift + Tab` to move to the previous cell
    - Type `/table` in the command palette to insert a table

#### **Method 3: Quick Insert**

Type `/table` in your note and select **Insert Table** from the menu. A dialog will let you choose the number of rows and columns.

#### **Tips for Tables**

|Tip|Description|
|---|---|
|**Minimum Columns**|At least 3 pipes per row (2 columns minimum)|
|**Separator Row**|Must have at least 3 dashes `---`|
|**Empty Cells**|Leave space between pipes: `|
|**Line Breaks**|Tables don't support line breaks inside cells natively|
|**Width**|Tables auto-adjust; use CSS for custom widths|

#### **Example with Content**

`| Project | Status | Due Date | | :------ | :----: | :------- | | Website | 🟢 Done | 2024-04-01 | | Report  | 🟡 In Progress | 2024-04-15 | | Design  | 🔴 Pending | 2024-05-01 |`

|Project|Status|Due Date|
|---|---|---|
|Website|🟢 Done|2024-04-01|
|Report|🟡 In Progress|2024-04-15|
|Design|🔴 Pending|2024-05-01|

---

### Quick Summary

|Feature|Syntax/Shortcut|
|---|---|
|**Table**|`|
|**Align Left**|`:---`|
|**Align Center**|`:---:`|
|**Align Right**|`---:`|
|**Insert Table**|`/table` command|
|**Navigate Cells**|`Tab` / `Shift + Tab`|

Would you like me to show you how to create a specific type of table, or do you need help with any other formatting features?

## Yes, Lumo

Here is a comprehensive **Obsidian Master Guide** tailored for you, Merson. Given your background in executive administration, music, and photography, this guide focuses on efficiency, structure, and leveraging Obsidian's unique linking capabilities to manage complex information.

---

# 📘 The Ultimate Obsidian Guide for Merson

## 1. Core Philosophy: The "Second Brain"

Obsidian is not just a note-taking app; it is a **Personal Knowledge Management (PKM)** system. Unlike traditional folders, it relies on **bi-directional linking** to connect ideas, mimicking how your brain associates concepts.

- **Local Files:** Everything is stored as plain `.md` (Markdown) files on your device. You own your data.
- **Graph View:** A visual map of how your notes connect.
- **Future-Proof:** Since files are plain text, they will be readable forever, even if Obsidian disappears.

---

## 2. Getting Started: Setup & Interface

### A. The Vault

A **Vault** is a folder on your computer that contains all your notes.

- **Recommendation:** Create one main vault (e.g., `Merson_Knowledge_Base`) or separate ones for `Work`, `Personal`, and `Creative`.
- **Sync:** Use **Obsidian Sync** (paid) or **Git/iCloud/Dropbox** (free) to sync across devices.

### B. Essential Settings

Go to **Settings** (Gear Icon) and enable these immediately:

1. **Core Plugins:**
    - **Templates:** For reusable note structures.
    - **Daily Notes:** For journaling or meeting logs.
    - **Outgoing Links:** To see where your links go.
    - **Backlinks:** To see who links _to_ your current note.
    - **Outline:** To see a table of contents for long notes.
2. **Editor:**
    - Enable **Live Preview** (default) for WYSIWYG editing.
    - Set **Default View** to "Reading View" if you prefer clean text, or "Edit View" for typing.

---

## 3. The Syntax Cheat Sheet (Quick Reference)

|Feature|Syntax|Example|
|---|---|---|
|**Heading**|`# H1` to `###### H6`|`## Project Alpha`|
|**Bold**|`**text**`|`**Urgent**`|
|**Italic**|`*text*`|`*Review*`|
|**Highlight**|`==text==`|`==Key Insight==`|
|**Strikethrough**|`~~text~~`|`~~Old Plan~~`|
|**List**|`-` or `1.`|`- Task 1`|
|**Task**|`- [ ]`|`- [ ] Call Client`|
|**Quote**|`>`|`> "Quote"`|
|**Code Block**|` ``` `|` ```python ... ``` `|
|**Inline Code**|`` ` ``|`` `variable` ``|
|**Link (Wiki)**|`[[Note]]`|`[[Meeting Notes]]`|
|**Embed**|`![[Note]]`|`![[Chart.png]]`|
|**Tag**|`#tag`|`#priority/high`|
|**Callout**|`> [!TYPE]`|`> [!WARNING]`|

---

## 4. Advanced Workflow Strategies

### A. The "Zettelkasten" Method (Slip Box)

Instead of filing notes in folders, link them.

1. **Fleeting Notes:** Quick thoughts captured anywhere.
2. **Literature Notes:** Summaries of what you read/watch.
3. **Permanent Notes:** One idea per note, fully fleshed out, linked to others.

- _Why?_ Over time, you build a web of knowledge where new ideas naturally emerge from connections.

### B. Daily Notes & Meeting Logs

Enable the **Daily Notes** plugin.

- **Usage:** Every morning, open your Daily Note. Log meetings, tasks, and random thoughts.
- **Linking:** When you mention a project, type `[[Project Name]]`. This creates the note automatically.
- **Benefit:** You never lose track of _when_ something happened.

### C. Templates for Consistency

Create a `Templates` folder.

- **Meeting Template:**
    
    `--- date: {{date}} participants: [] tags: [meeting] --- # Meeting: {{title}} ## Agenda -  ## Notes -  ## Action Items - [ ]` 
    
- **How to use:** Type `/template` and select your template to populate the note instantly.

### D. Dataview (The Superpower)

Install the **Dataview** community plugin. It turns your vault into a database.

- **Example:** List all unfinished tasks from the last week.
    
    ` ```dataview TASK FROM #task WHERE !completed AND file.day >= date(today) - dur(7 days) ``` `
    
- **Use Case:** Perfect for tracking "Executive Online Admin" tasks or photography project deadlines.

---

## 5. Visualizing Your Knowledge

### A. Graph View

- **Access:** Click the "Graph" icon in the sidebar.
- **Filters:** Filter by tags (e.g., show only `#work` notes) or folders.
- **Insight:** See clusters of connected ideas. If a note has no connections, it might be an orphan needing context.

### B. Canvas (Infinite Whiteboard)

- **Feature:** Drag and drop notes, images, and web pages onto an infinite canvas.
- **Use Case:**
    - **Photography:** Map out a photo shoot plan with mood board images and shot lists.
    - **Music:** Arrange song structures or practice schedules visually.
    - **Admin:** Map out complex workflows or organizational charts.

---

## 6. Essential Community Plugins

_Go to Settings > Community Plugins > Browse._

|Plugin|Purpose|Why You Need It|
|---|---|---|
|**Dataview**|Database queries|Automate lists and reports.|
|**Templater**|Advanced templates|Dynamic dates, prompts, and scripts.|
|**Excalidraw**|Hand-drawn diagrams|Sketch ideas, flowcharts, or music theory.|
|**Kanban**|Trello-like boards|Manage projects (e.g., "Photo Shoots" or "Admin Tasks").|
|**Calendar**|Visual calendar|Jump to daily notes easily.|
|**Omnisearch**|Better search|Finds text inside PDFs and images (OCR).|

---

## 7. Best Practices for Merson

### For Executive Administration

- **Properties (YAML Frontmatter):** Use metadata at the top of notes for sorting.
    
    `--- status: active priority: high client: TechCorp ---`
    
- **Kanban Boards:** Track project status (To Do, In Progress, Done).
- **Meeting Agendas:** Use templates to ensure consistency.

### For Photography & Music

- **Embed Media:** Drag and drop photos directly into notes. Use `![[photo.jpg]]` to embed them inline.
- **Excalidraw:** Sketch chord progressions or composition layouts.
- **Tagging:** Use hierarchical tags like `#music/classical/piano` or `#photo/portrait/studio`.

### For Tech & Learning

- **Code Blocks:** Document scripts with syntax highlighting.
- **Mermaid Diagrams:** Visualize system architecture or logic flows.
- **Linking:** Connect concepts (e.g., link `[[Python]]` to `[[Data Analysis]]`).

---

## 8. Troubleshooting & Tips

- **Broken Links:** If you rename a note, Obsidian automatically updates all links to it.
- **Orphaned Notes:** Use the "Orphaned Notes" filter in the Graph to find notes with no connections.
- **Performance:** If the vault gets huge (10k+ notes), disable heavy plugins like Excalidraw on startup.
- **Mobile:** The mobile app is excellent. Use voice-to-text for quick capture.

---

## 9. Next Steps

1. **Create your first Daily Note.**
2. **Set up a "Templates" folder** with a Meeting and Project template.
3. **Install Dataview** and try a simple query.
4. **Explore the Graph** to see your connections form.

Would you like me to generate a specific **template** for your "Cousin Crew Executive Online Administrator" role, or perhaps a **Dataview query** to track your photography projects?