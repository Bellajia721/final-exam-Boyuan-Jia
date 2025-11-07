# Final Exam – Boyuan Jia

A self-contained repo for the Python final exam. It includes an iterative prompt‑engineering section, debugging & correction tasks, an API error‑handling refinement, and a manual implementation with reflection.

## Repo contents

- `Final_Exam.ipynb` — the main notebook containing all sections (1–4) with headings that match the rubric.  
- `conversation_log.txt` — the exact prompts and AI responses used for each subsection, plus course‑constraint checks.  
- `README.md` — you are reading it.

---

## How to open / run

**Option A – Google Colab (recommended):**
1. Open the notebook and click the “Open in Colab” badge at the top.
2. Run cells from top to bottom. Each subsection is clearly labeled (e.g., *Section 1.1*, *Section 2.2*, etc.).

**Option B – Local Jupyter:**
1. Create/activate a Python 3 environment.
2. `pip install notebook`
3. `jupyter notebook` → open `Final_Exam.ipynb`.

> Note: In Section **2.2** there’s a beginner‑friendly CLI script (`task_manager.py`) included inside the notebook. You can copy it into a standalone file and run with `python task_manager.py` if you wish to test outside the notebook.

---

## Assessment map (where to find what)

- **Section 1: Iterative Prompt Engineering (30 marks)**
  - **1.1 Initial Prompt & Pseudocode (8 marks)**  
    Problem restatement, inputs/outputs, example walkthrough, modular pseudocode, and main loop.
  - **1.2 Two Prompt Refinements (12 marks)**  
    (a) Robustness & defensive programming (validation, duplicates, file I/O guards)  
    (b) User‑experience polish (clean menu, counts, friendly summaries, exit confirm)
  - **1.3 Critical Analysis (10 marks)**  
    ~150 words synthesising Weeks 2–8 concepts and the iteration outcomes.

- **Section 2: Debug & Correct with AI (25 marks)**
  - **2.1 Error Identification (10 marks)**  
    Naming/reference mismatches, bounds/type checks, user messaging, etc.
  - **2.2 Fix & Manual Rewrite (15 marks)**  
    Clean beginner version using lists/dicts, while‑menu, simple try/except, and save/load.

- **Section 3: WeatherWise API (20 marks)**
  - **3.1 Issue Analysis (6 marks)**  
    Bare `except`, missing status check, JSON access safety, input guards.
  - **3.2 Function Refinement (10 marks)**  
    Intro‑level error handling (simple try/except, conditional checks, `None` on failure).
  - **3.3 Comparison Analysis (4 marks)**  
    2 similarities, 2 differences, 1 course connection, 1 improvement area.

- **Section 4: Manual Implementation & Reflection (25 marks)**
  - **4.1 Manual Implementation (15 marks)**  
    Week‑4/5‑level minimal task manager (`add/list/remove`) with doctest‑style examples.
  - **4.2 Course‑Connected Reflection (10 marks)**  
    Planning vs coding, loops/guards, error‑handling mindset, and learning transfer.

---

## `conversation_log.txt` — contents & requirements

This file mirrors the exact prompts you issued and the AI responses for each subsection and serves as the reproducibility trail for marking.

**Minimum requirements checklist for `conversation_log.txt`:**  
- [ ] Include at least one prompt/response for every subsection: **1.1, 1.2, 2.1, 2.2, 3.1, 3.2, 3.3, 4.1, 4.2**.  
- [ ] Keep each log short (about **5–10 lines**).  
- [ ] For every “Course Constraint Check,” explicitly mention the **course week or concept** (e.g., Week 4 modular design; Week 6 defensive programming; Week 8 JSON handling).  
- [ ] Save it **alongside** `Final_Exam.ipynb` in the repo root.  
- [ ] Use **UTF‑8 plain text** and name the file exactly `conversation_log.txt`.

---

## Quick marking checklist

- [ ] **1.1** Clear problem restatement, I/O, example, modular pseudocode, main flow  
- [ ] **1.2** Two refinements: robustness + UX; both keep to intro‑level constructs  
- [ ] **1.3** Critical analysis (~150 words) with Week references  
- [ ] **2.1** Concrete beginner‑style bug list with symptoms & locations  
- [ ] **2.2** Working beginner rewrite (lists/dicts, while‑menu, simple try/except, save/load)  
- [ ] **3.1** API failure‑point analysis tied to course content  
- [ ] **3.2** Refined function with basic guards, status check, JSON safety, returns `dict`/`None`  
- [ ] **3.3** 2× similarities, 2× differences, course link, improvement area  
- [ ] **4.1** Manual (no AI) minimal implementation at Week‑4/5 scope + doctest‑style examples  
- [ ] **4.2** Reflection connects workflow to Weeks 3–8; learning transfer stated  
- [ ] `conversation_log.txt` present and aligned with sections (short, focused entries).

---

## Academic integrity

- All code in Section **4.1** is authored manually to match Week‑4/5 constraints.  
- Where AI was used (Sections 1–3), the exact prompts and outputs are preserved in `conversation_log.txt` for transparency.

---

## License

This exam submission is provided for assessment purposes only. Do not reuse without permission.
