# HCI Intelligent Interactive Systems Assignment2 Prototype

## Project Status
| Feature | Status |
|---|---|
| Note input UI, process‑note button | Implemented |
| Suggestion chips for summary style | Implemented |
| Preference inspect / edit / forget panel | Implemented |
| Confidence score display & UI feedback toast | Implemented |
| Simulated context‑assembly logic (select‑order‑budget‑record) | Simulated |
| Simulated LLM note‑summary mock outputs | Simulated |
| Real LLM API connection | Planned |
| RAG document retrieval for grounding summaries | Planned |
| Persistent dated episodic session memory | Planned |

## Technology Stack
- Front‑end: HTML, CSS, vanilla JavaScript
- No external LLM API keys included. All model outputs are hard‑coded mock simulation for HCI interaction demonstration.

## How to run
1. Clone repository
2. Open index.html in web browser
3. Paste note text, select summary style option and press "Process notes"
4. Open panel "What I remember about you" to inspect/edit/delete system‑inferred learning preferences.

## Development Record
- Commit 52f21ac: Added explicit preference‑management panel. Iteration: initial design silently updated inferred preferences without user visibility. Revised following Week4 context‑engineering lectures: system inferences must be inspectable, editable and forgettable.
- Added confidence score display to mitigate expectation gulf (Week1 / Week3 lecture content).
- Implemented suggestion‑chip UI to shift from recall to recognition and reduce extraneous cognitive load.

## AI Assistance Declaration
Generative AI tools were used to draft initial UI markup and text snippets. All interaction design choices, design rationale arguments and HCI concept mappings were manually reviewed, revised and aligned to Weeks1‑4 module content by the author. No generated code was used without manual checking and modification.
