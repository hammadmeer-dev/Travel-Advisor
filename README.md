## Travel-Advisor Repository (ML)

# Travel-Advisor – AI/ML Engine for Traveler Platform

This repository contains the **machine learning engine** for the Traveler platform. It provides **AI-powered travel recommendations** used by the backend server ([Traveler](https://github.com/hammadmeer-dev/Traveler)).

**Frontend repository:** [Traveler Frontend](https://github.com/hammadmeer-dev/traveler_client)
**Backend repository:** [Traveler Backend](https://github.com/hammadmeer-dev/Traveler)

---

## Visit Online : [Traveler](https://truetraveler.netlify.app)
---
## Overview

* **ML Algorithm:** K-Nearest Neighbors (KNN) with Cosine Similarity
* **Inputs:** district (e.g., Punjab, KPK, Sindh), category (e.g., Fort, Valley, Museum)
* **Outputs:** Top 5 recommended destinations
* **Tools:** Python, Flask, Scikit-learn, Pandas, NumPy, SentenceTransformer
* **Data:** `Tourist Destinations.csv`

> This engine is minimal in functionality but can be expanded. Contributions are welcome.

---

## Requirements

* Python 3.x
* Flask, Scikit-learn, Pandas, NumPy, SentenceTransformer

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the ML Engine

1. **Clone the repository**

```bash
git clone https://github.com/hammadmeer-dev/Travel-Advisor.git
cd Travel-Advisor
```

2. **Start Flask server**

```bash
python app.py
```

3. **Connect with Backend**
   Ensure the backend ([Traveler](https://github.com/hammadmeer-dev/Traveler)) points to the ML API (`ML_API_URL=http://localhost:5001`) to fetch AI recommendations.

---

## Contribution

* Fork → Branch → Commit → Push → Pull Request

---

## License

MIT License

---

## Contact

Hammad Farooq Meer – [GitHub](https://github.com/hammadmeer-dev)
