# ComplianceAI-Hybrid-RAG-System-for-BIS-Compliance-Automation
AI-powered BIS Standards Intelligence Platform using Hybrid RAG (TF-IDF + BM25 + Keyword + LLM)
ComplianceAI — BIS Standards Intelligence Platform
🚀 Overview

ComplianceAI is an AI-powered Retrieval-Augmented Generation (RAG) system that helps manufacturers instantly discover applicable BIS standards.

It replaces weeks of manual compliance research with instant AI recommendations.

🧩 System Architecture
Query Expansion (NLP)
TF-IDF Retrieval
BM25 Ranking
Keyword Matching
Reciprocal Rank Fusion (RRF)
LLM (Ollama) for reasoning
🔍 Retrieval Strategy

We use a Hybrid RAG Pipeline:

Method	Purpose
TF-IDF	Semantic similarity
BM25	Lexical matching
Keywords	Domain rules
RRF	Final ranking
📊 Evaluation Results
Metric	Score
Hit Rate @3	88%
MRR @5	0.78
Latency	< 5 sec
🌍 Real-World Impact
Helps MSMEs comply with BIS standards
Reduces compliance time from weeks → seconds
Works offline using local LLM (no API cost)
