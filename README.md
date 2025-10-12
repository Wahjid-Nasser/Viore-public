# Viore.ai — The Intelligence Layer for Media (starting with video)

Viore.ai transforms unstructured media into structured, searchable intelligence.  
It extracts meaning across modalities — speech, audio, visuals, and text — beginning with video and evolving toward unified media understanding.

---

## 🚀 Overview

Viore is a hybrid intelligence engine that processes **video, audio, and text** at scale.  
It ingests, transcribes, segments, embeds, and ranks media content — making every spoken word, tone, and visual moment searchable and analyzable.

Key pillars:
- **Hybrid Search:** Combines symbolic keyword (`tsvector`) and semantic (`pgvector`) search.
- **Segment Intelligence:** Breaks content into coherent intervals across modalities.
- **Cross-Modal Reasoning:** Links speech, sound, and visuals into a unified context graph.
- **Scalable Architecture:** Modular pipelines for ingestion, transcription, embedding, and retrieval.

---

## 🧩 Core Components

| Module | Description |
|---------|--------------|
| `media_downloader.py` | Extracts and normalizes video or audio sources |
| `transcriber.py` | Generates transcripts using Faster-Whisper |
| `chunker.py` | Splits content into pause-aware or fixed-window chunks |
| `embedder.py` | Produces embeddings for text, audio, and visual cues |
| `search.py` | Executes hybrid retrieval with Reciprocal Rank Fusion (RRF) |
| `orchestrator.py` | Coordinates multimodal processing pipelines |

---

## 🧠 Future Expansion

- Visual embeddings (CLIP-based) for object and scene reasoning  
- Audio-emotion and acoustic event embeddings  
- Text-only ingestion for metadata and contextual linkage  
- Temporal contradiction detection and narrative alignment  
- Multimodal ranking and cross-media reasoning  

---

## ⚙️ Setup (Preview)

```bash
git clone https://github.com/viore-ai/viore
cd viore
pip install -r requirements.txt
python orchestrator.py --media "https://youtube.com/watch?v=..."
```

---

## 🧭 Philosophy

Viore.ai isn’t just about video — it’s about **understanding media**.  
Every frame, sound, and word holds insight. Viore’s mission is to make them **discoverable, interpretable, and interconnected** — the foundation of a true media intelligence layer.
