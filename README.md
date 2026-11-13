# Nithisha

I build LLM systems, then spend most of my time on what happens when they break. The retry that never fires, the fallback model that's also down, the prompt injection sitting inside someone's README.

Mostly Python. TypeScript when the backend needs a face.

### Things I've built

**[Athenaeum](https://github.com/theCodeForgerHQ/athenaeum-multi-agent-system)**: a multi-agent tutor that cites everything it says and grades exams it can't be sweet-talked out of. Every answer goes through an injection gate, a router and a grounding check, and you can open the trace and watch it happen. I threw 232 attack prompts at the safety layer before I trusted it. Won the student award at Microsoft's Agents League.

**[Gappy](https://github.com/theCodeForgerHQ/Gappy)**: an agent that fixes bugs in Python repos, with one rule: a fix only counts when a failing pytest you wrote turns green. The agent writes the patch, never the test. A second agent then checks the diff for cheating (deleted tests, hard-coded answers) before a human approves the PR. Won the Gappy AI hackathon.

**[Nucleus AI](https://github.com/theCodeForgerHQ/Nucleus-AI)**: RAG over Confluence. Hybrid retrieval, cross-encoder reranking, and an NLI pass that catches answers contradicting their own sources.

**[Resident](https://github.com/NithishaVenkatesh/Paritok)**: Paritok's compressor returns an empty 200 when a chunk is irrelevant to your query. Every client I read treated that as an error and sent the original text anyway. Read it as a zero-token verdict instead and a whole repo fits in one context window.

**[upi-agent-conformance](https://github.com/NithishaVenkatesh/upi-agent-conformance)**: checks a merchant's payment terms against RBI/NPCI circulars before any money moves, and quotes the clause when it refuses.

**[UrbanTwin LUMPI](https://github.com/NithishaVenkatesh/urban-finals)**: 3D LiDAR detectors trained only on synthetic CARLA data, tested on real roadside scans from Hannover. 3rd place at the DriveX workshop, ECCV 2026.

**[wolff](https://github.com/theCodeForgerHQ/wolff)**: quote-to-cash for freelancers. Quotes, e-signatures, GST invoices, Razorpay, and an assistant that only answers from your own documents.

### Also

- AIR 13 at NIDAR, the national drone challenge
- Finalist, Japan Automotive AI Challenge 2026
- Top 5, Techathon 2.0

### Elsewhere

[portfolio](https://nithisha.vercel.app) · [linkedin](https://linkedin.com/in/nithisha-v) · [email](mailto:nithishaleni1806@gmail.com)
