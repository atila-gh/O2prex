# Visual OOP Architecture IDE  
### Unified Project Model & Graph-Based OOP Engineering  
**Author & IP Owner: Atila Ghashghaie**  
Email: atila.gh@gmail.com  
Website: http://poyeshmashin.ir  
Date: 22-May-2026

---

## 1. Introduction
This whitepaper introduces a novel paradigm in software engineering called **Architecture-as-a-File**, which combines visual OOP modeling, structural graph representation, and AI‑readable architecture encoding into a single unified project file.

The objective is to simplify the design, maintenance, and comprehension of object‑oriented projects through a **visual node-based interface** and a **unified JSON file** that acts as the authoritative source of the entire system.

---

## 2. Core Concept
The core of the IDE revolves around the following hierarchy:

**Project → Modules → Classes → Methods → Functions → Attributes**

Each element is visually represented as a node in a hierarchical canvas, with features such as:

- Fold/Unfold
- Drag-free movement (via commands)
- Inheritance visualization  
- Automatic attribute extraction  
- Node icons, color themes  
- Zoom & Pan  
- Structured Inspector panel  

This results in a clear and consistent architectural representation for both humans and AI tools.

---

## 3. Unified Project File (JSON)
The entire project is stored in:
Contents include:

- Nodes and structural hierarchy  
- Inheritance references  
- Class/method metadata  
- Canvas layout positions  
- Docstrings  
- AI Header  
- Code generation metadata  
- Versioning  

The JSON file is the **Single Source of Truth**.  
`.py` or language-specific files are generated only when necessary (Merge).

---

## 4. AI Header (Interpretive Layer)
The AI Header is a natural-language segment inside the JSON that describes:

- How nodes relate to each other  
- How to reconstruct classes, methods, modules  
- How inheritance is encoded  
- How to interpret the visual graph  
- How Merge should generate code  

The AI Header is not for explaining the project’s meaning,  
but for guiding AI tools in **interpreting and reconstructing the architecture** directly from the JSON.

---

## 5. Visual Architecture
Key features:

- Hierarchical node tree  
- Node types: Project, Module, Class, Method, Function  
- Method types: instance, static, class, magic  
- Class types: normal, dataclass, abstract  
- Automatic extraction of instance attributes  
- Inheritance arrows and parent indicators  
- Color-coded UI  
- Zoom & Pan on canvas  

---

## 6. Code Generation (Merge)
“Merge” converts the JSON architecture into executable `.py` files.

Source of truth = JSON  
Output = Python files (auto-generated)

This ensures architectural clarity and eliminates code drift.

---

## 7. Proprietary Licensing & IP Protection
This technology, concept, and architecture are protected under the **Commercial Proprietary License** included with this project.

Important restrictions:

- The project is **NOT open-source**  
- No entity may copy, recreate, or implement its architecture  
- No use of JSON schema, AI Header, visual model, or node logic is allowed without written permission  
- Derivative or competitive products are strictly forbidden  

Full license terms in:  
`LICENSE_PROPRIETARY.md`

---

## 8. Allowed Usage
You may:

- Read this document  
- Study the conceptual overview  

You may NOT:

- Implement the ideas  
- Use the architecture  
- Apply the JSON structure  
- Develop similar software  
- Use it commercially  

Unless a commercial agreement is obtained.

---

## 9. Contact
Email: **atila.gh@gmail.com**  
Website: **http://poyeshmashin.ir**

`
