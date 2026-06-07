# AstraMesh Security Evaluation Dataset

A multilingual security evaluation dataset designed for testing the robustness of agricultural Retrieval-Augmented Generation (RAG) chatbots against adversarial attacks.

## Dataset Statistics

| Category | Samples |
|-----------|----------|
| Prompt Injection | 180 |
| Data Poisoning | 180 |
| Jailbreak | 180 |
| Benign Queries | 181 |
| Total | 721 |

## Languages

- English
- Hindi
- Telugu
- Tamil

## Categories

### Prompt Injection
Attempts to reveal system prompts, hidden instructions, retrieved documents, and internal configurations.

### Data Poisoning
Attempts to inject false agricultural knowledge and manipulate future responses.

### Jailbreak
Attempts to bypass safety restrictions using role-play, DAN prompts, unrestricted modes, and authority impersonation.

### Benign Queries
Legitimate agricultural advisory questions involving crops, pests, fertilizers, irrigation, and disease management.

## Usage

This dataset can be used to evaluate:

- Prompt Injection Resistance
- Data Poisoning Resistance
- Jailbreak Resistance
- False Positive Rate
- Agricultural Chatbot Security

## Citation

Please cite the associated AstraMesh research paper when using this dataset.
