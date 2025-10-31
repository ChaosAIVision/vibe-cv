🧑‍💻 AI/GenAI Engineer Intern
Email: [Ẩn] | LinkedIn: [Ẩn] | Mobile: (+84) [Ẩn] | Github: [Ẩn]

🎓 EDUCATION
Hanoi University of Civil Engineering | Ha Noi, Viet Nam

Major: BSc of Computer Science | CPA: 3.21 | Sep 2022 - Jun 2026(Expected)

- Awarded Scholarships for Good Academic Achievements | 2023, 2024

🛠️ SKILLS
Programming Languages: Python, SQL

AI frameworks: Pytorch, (Sentence)Transformers, PEFT, Langchain, Langgraph, Unsloth

Web frameworks: FastAPI

Database: PostgreSQL, Pinecone

Tools: Git, Docker, Linux, GCP Vertex AI

Languages: Vietnamese (native), English (B2)

📝 PROJECTS
• Image to LaTeX [Github]
[Python, Pytorch, FastAPI, ...]

Xây dựng mô hình học sâu từ chuẩn bị dữ liệu, huấn luyện mô hình và triển khai qua API để chuyển đổi hình ảnh công thức toán học thành mã LaTeX.

Triển khai mô hình kết hợp Resnet-18 backbone để trích xuất đặc trưng hình ảnh với một Transformer decoder cho việc tạo chuỗi.

Huấn luyện trên tập dữ liệu IM2LATEX-100K, tương ứng với mã LaTeX cho mỗi hình ảnh.

Kết quả: BLEU-1: 81.06%, exact match (EM): 25.15%, character error rate (CER): 14.28%, edit distance (ED): 15.29 trên tập kiểm thử.

• RAG-based Knowledge Assistant [Github]
[Python, Langchain, OpenAI, Cohere, Streamlit, Postgres+pgvector, ...]

Xây dựng một hệ thống RAG (Retrieval-Augmented Generation) để truy vấn dữ liệu từ cả các tài liệu cục bộ và URL, tăng cường khả năng truy cập linh hoạt.

Triển khai kiến trúc hai giai đoạn: tìm kiếm ngữ nghĩa (semantic search) + Xếp hạng lại (Cohere reranking), cải thiện độ liên quan của câu trả lời dựa trên tìm kiếm vector.

Kiến trúc đầu cuối bao gồm: phân tích tài liệu (Docling) và trích xuất URL (trafilatura), chia đoạn văn bản đệ quy, tạo embedding (OpenAI embedding generation), và lưu trữ trong PostgreSQL+pgvector.

Phát triển một giao diện thân thiện với người dùng bằng Streamlit và được đóng gói bằng Docker.

• Fine-tuning Gemma Models for Medical QAs and Retrieval [Github]
[Python, Transformers, PEFT, Unsloth, WanDB, ...]

LoRA fine-tuned embedding-Gemma-300m embedding model trên tập dữ liệu viet-med-qa (~10k rows) [Huggingface].

Kết quả: accuracy@1: 44% -> 85%, ndcg@10: 0.60 -> 0.92, mrr@10: 0.55 -> 0.89...

Supervised fine-tuned gemma-3b-it model trên tập dữ liệu VietnameseHealth-QA-dataset (~16k rows) [Huggingface].