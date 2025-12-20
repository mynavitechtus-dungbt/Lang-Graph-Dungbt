# LangGraph Tutorial Series

## 📚 Giới Thiệu

**LangGraph** là một thư viện mạnh mẽ để xây dựng các ứng dụng AI với state machines và graph-based workflows. Repository này chứa các bài học và ví dụ thực hành về LangGraph, từ cơ bản đến nâng cao.

> *"Training LangGraph to make salary go to the moon, get the money and give all to my wife."* 💰🌙

## 🔑 Khái Niệm Cơ Bản

- **State**: Dictionary chứa dữ liệu truyền qua các nodes
- **Node**: Function nhận state và trả về state đã cập nhật
- **Edge**: Kết nối giữa các nodes (fixed hoặc conditional)
- **Graph**: Tập hợp nodes và edges được compile thành ứng dụng

## 📖 Các File Notebook

### 1. Your First LangGraph Example — Turning Logic into Flow
   - Giới thiệu cơ bản về LangGraph
   - Tạo graph đơn giản với 1 node
   - Hiểu cách state được truyền qua nodes

### 2. Structured States & Multi-Step Reasoning Explained
   - Làm việc với structured states (TypedDict)
   - Multi-step processing với nhiều nodes tuần tự
   - Quản lý state phức tạp hơn

### 3. Conditional Routing in LangGraph
   - Conditional routing - điều hướng dựa trên điều kiện
   - Sử dụng conditional edges
   - Quyết định động trong graph flow

### 4. Multi-Branch Decision Flows Explained
   - Graph phức tạp với nhiều nhánh
   - Xử lý nhiều luồng xử lý song song
   - Advanced conditional routing patterns

### 5. Building Loops & Iterative Logic in LangGraph
   - Tạo loops và logic lặp lại
   - Xử lý iterative workflows
   - Quản lý state trong vòng lặp

### 6. State-Based Conversational AI Tutorial
   - Xây dựng conversational AI với LangGraph
   - Quản lý conversation state
   - Tích hợp với LLM models

### 7. LangGraph Tool Nodes Explained
   - Sử dụng tool nodes trong LangGraph
   - Tích hợp external tools và APIs
   - Tool calling patterns

## 🚀 Cài Đặt

### Yêu Cầu
- Python 3.11+
- pip

### Các Bước Cài Đặt

1. **Kích hoạt virtual environment:**
   ```bash
   source venv/bin/activate
   ```

2. **Cài đặt dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Khởi chạy Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   
   Hoặc sử dụng JupyterLab:
   ```bash
   jupyter lab
   ```

### Dependencies

- `jupyter>=1.0.0` - Jupyter notebook environment
- `langgraph>=1.0.0` - LangGraph library
- `ipykernel>=6.0.0` - IPython kernel for Jupyter
- `python-dotenv>=1.0.0` - Environment variable management
- `langchain-google-genai>=1.0.0` - Google GenAI integration for LangChain

## 📝 Cấu Trúc Project

```
LangGraph/
├── 1.Your First LangGraph Example — Turning Logic into Flow.ipynb
├── 2.Structured States & Multi-Step Reasoning Explained.ipynb
├── 3.Conditional Routing in LangGraph.ipynb
├── 4.Multi-Branch Decision Flows Explained.ipynb
├── 5.Building Loops & Iterative Logic in LangGraph.ipynb
├── 6.State-Based Conversational AI Tutorial.ipynb
├── 7.LangGraph Tool Nodes Explained.ipynb
├── requirements.txt
├── README.md
└── venv/                    # Virtual environment (gitignored)
```
