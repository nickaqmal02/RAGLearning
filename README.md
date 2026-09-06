# RAG Pipeline Personal Note

## Why This Project
- Building a RAG system for searching PDF
- Learning LangChain, ChromaDB, and embedding models
- Practice class-based architecture with logging

## What I Learned ?
- **Deduplication is CRITICAL** for RAG
- Always deduplicate before chunking
- Clear vector store when rebuilding
- Use content hashing for deduplication

## Gotchas & Fixes
| Issue | Solution |
|-------|----------|
| Duplicate results | Add deduplication in PDF loading |
| ChromaDB duplicates | Set clear_existing=True |
| Slow embeddings | Use GPU (mps on Mac) |
| Missing logs | Add logging to all classes |

## Personal Notes
- **Date**: 2026-09-06
- **Status**: ✅ Retrieval working
- **Next**: Add LLM for answer generation
- **Reference**: Steve Jobs biography PDFs
