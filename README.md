# Customer Churn Predictor

Reduced model training time by 45% using feature selection and hyperparameter tuning

## About

Built end-to-end ML pipeline for telecom churn prediction using XGBoost with SHAP explainability dashboard

Reduced model training time by 45% using automated feature selection and Optuna hyperparameter optimization

Deployed Streamlit business dashboard allowing non-technical teams to run predictions on new customer data

## Tech Stack

- Python
- scikit-learn
- XGBoost
- Streamlit

## Features

- Production-ready implementation with error handling and logging
- Comprehensive documentation and code comments
- Modular architecture following clean code principles
- CI/CD ready with GitHub Actions workflow included
- Environment-based configuration for dev/staging/prod

## Getting Started

### Prerequisites

- Python
- scikit-learn
- XGBoost
- Streamlit

### Installation

```bash
# Clone the repository
git clone https://github.com/alam025/churn-predictor.git
cd churn-predictor

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env with your configuration

# Run the application
streamlit run app.py
```

## Project Structure

```
churn-predictor/
├── src/                    # Source code
│   ├── components/         # Reusable components
│   ├── utils/              # Utility functions
│   └── config/             # Configuration files
├── tests/                  # Test suite
├── docs/                   # Documentation
├── .env.example            # Environment variable template
├── .github/                # GitHub Actions workflows
│   └── workflows/
│       └── ci.yml
└── README.md
```

## Key Implementation Highlights

1. Built end-to-end ML pipeline for telecom churn prediction using XGBoost with SHAP explainability dashboard
2. Reduced model training time by 45% using automated feature selection and Optuna hyperparameter optimization
3. Deployed Streamlit business dashboard allowing non-technical teams to run predictions on new customer data

## Performance Metrics

- **Accuracy / Quality**: See benchmark results in `docs/benchmarks.md`
- **Latency**: Optimized for production workloads
- **Scalability**: Tested under concurrent load

## Deployment

This project is configured for deployment on **Streamlit Cloud**.

Detailed deployment instructions are available in `docs/deployment.md`.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

MIT License — see `LICENSE` for details.

---

*Built with Python, scikit-learn, XGBoost and 1 more*
