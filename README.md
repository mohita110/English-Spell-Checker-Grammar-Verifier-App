# 📝 Compiler-Based English Spelling & Grammar Checker

A web-based application that performs English spelling identification and correction using a **compiler-based approach** — integrating lexical analysis, parsing techniques, and grammar validation into an attractive frontend interface.

![Demo Screenshot](https://via.placeholder.com/800x400?text=Spell+Checker+Demo)

## ✨ Features

- **🔤 Lexical Analysis** – Tokenizes input text into words, punctuation, numbers, and spaces
- **🌳 Recursive Descent Parser** – Builds an Abstract Syntax Tree (AST) from token streams
- **✅ Spelling Validation** – Dictionary-based checking with Levenshtein distance suggestions
- **📖 Grammar Rules** – Detects common grammar issues (e.g., "a apple" → "an apple")
- **📁 File Upload** – Supports `.txt` and `.md` files up to 50KB
- **📊 Visual Pipeline** – Real-time compiler phase tracking (Lexer → Parser → Spell → Grammar → Output)
- **💡 One-Click Corrections** – Apply suggested fixes instantly
- **📋 Copy Output** – Copy corrected text to clipboard

## 🏗️ System Architecture (Compiler Pipeline)

| Phase | Technique | Output |
|-------|-----------|--------|
| **Lexical Analysis** | Character scanning & tokenization | Token stream (WORD, PUNCT, NUMBER, SPACE) |
| **Parsing** | Recursive descent parser | Abstract Syntax Tree (Document → Sentences → Words) |
| **Spell Checking** | Dictionary lookup + Levenshtein distance | Error list with suggestions |
| **Grammar Checking** | Pattern-matching rules | Grammar warnings & auto-fixes |
| **Output Generation** | AST traversal & reconstruction | Corrected text + compiler log |


## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Fonts:** Google Fonts (DM Serif Display, DM Sans, DM Mono)
- **No external dependencies** – Pure vanilla implementation

