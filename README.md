 What is the goal?

"""
O objetivo criar um projeto voltado a comunidade cristã.
"""

## Estrutura para as etapas da entrega do projeto

- Etapa de Pesquisa;
- Etapa de Estudo preliminar;
- Anteprojeto;
- Projeto final;

/// O que entregar na etapa de pesquisa:
    - Tema (Introdução, problemática, objetivo da pesquisa, objetivo do projeto) 
    - Referências de projetos existêntes (mínimo 2)

/ Instruções para pesquisa
    - Permitido uso de ia apenas para a escrita e geração de imagens. Para gerar código, não.
    - Permitido uso da ia para aprender a linguagem computacional e sugestões de ideia, mas nada dele gerar código.
    - Criar algum arquivo para os moderadores poderem fazer uma apresentação do conteúdo gerado pela pesquisa


    
## Repositório referencia de projetos para iniciantes 
[App Ideas Collections - credit_florinpop17](https://github.com/florinpop17/app-ideas)


## Sugestões de projetos

Project 1: Smart Loan & Credit Risk Decision Engine (FinTech)
Division of Work (3 People):
- Person 1 — Input Collection & Data Normalization:
- Collects CLI inputs: applicant name, age, income, existing debt, employment flag, and guarantor flag.
- Validates data types, handles None defaults for uninitialized fields, and ensures variables use clean snake_case.
- Person 2 — Core Eligibility & Logic Engine:
- Implements complex multi-condition boolean expressions (and, or, not, De Morgan's laws) to check minimum criteria (age $\ge 18$, debt-to-income ratio thresholds, employment status).
- Computes financial risk metrics using arithmetic shortcuts (risk_score += ..., debt_ratio = debt / income).
- Person 3 — Risk Tiering & Formatted Reporter:
- Builds the nested if/elif/else trees to assign risk tiers ("Prime", "Standard", "Subprime", "Rejected").
- Calculates interest adjustments and prints a clean final summary report using Python f-strings.
Project 2: Interactive Automated Health & Fitness Diagnostic System (HealthTech)
Theme: Diagnostic assessment tool that evaluates lifestyle, biometric stats, and habits to produce personalized health risk indexes and workout plan recommendations.
How It Works:
Users enter biometric data (age, height, weight, resting heart rate, weekly workout hours, smoking/diet booleans). The program calculates BMI, estimates metabolic rate, evaluates cardiovascular and lifestyle risk categories, and delivers structured advice.
Direct Connection to Your Notes:
- Arithmetic & Type Conversion: Calculates BMI (weight / (height ** 2)), target heart rate zones, and daily caloric needs using int and float.
- Modulo (%): Determines workout cycle phases and rest-day rotation (e.g., day_number % 2 == 0 for alternating split days).
- Logical Combinations:
# High cardiovascular risk flag
is_high_risk = (resting_hr > 90 or not exercises_regularly) and (age > 45 or is_smoker)
- Decision Trees (if/elif/else):
- BMI classifications: Underweight, Normal, Overweight, Obese.
- Caloric target and workout split tiering.
Division of Work (3 People):
- Person 1 — Biometrics Ingestion & Sanitization:
- Collects user health stats, validates ranges (e.g., positive non-zero numbers), sets None states for optional inputs (like heart ra
- Person 2 — Biometric Calculation & Risk Scoring:
- Implements formulas (BMI, Basal Metabolic Rate, heart-rate zones) using arithmetic operators and shorthand (+=, -=, *=).
- Applies compound boolean conditions to flag warning metrics.
- Person 3 — Diagnostic Tree & Summary Generator:
- Builds the multi-tier if/elif/else recommendation matrix.
- Formats the final diagnostic profile output with clear explanations and next steps.
Project 3: E-Commerce Smart Pricing, Fraud & Discount Engine (E-Commerce Automation)
Theme: An e-commerce backend simulator that evaluates shopping cart contents, calculates tiered dynamic discounts, verifies promo rules, and detects potentially fraudulent orders.
How It Works:
Simulates order checkout: takes item counts, customer membership tier, order subtotal, delivery distance, and shipping preferences. It calculates taxes, applies layered discounts, runs anti-fraud checks, and generates an itemized invoice.
Direct Connection to Your Notes:
- Empty State Handling (None): Tracks coupon codes or discount rates that have not yet been applied (applied_coupon = None).
- Modulo Operator (%): Implements "Buy X, get 1 free" deals or free shipping on every $N$-th transaction, plus check-digit validation on simulated payment cards.
- Logical Expressions & De Morgan’s Laws:
# Free shipping check: (VIP member OR cart >= $100) AND NOT international delivery
gets_free_shipping = (is_vip or subtotal >= 100.0) and not is_international

# Fraud detection flag
flag_fraud = (order_total > 5000 and not is_verified_user) or is_blacklisted
- Arithmetic Shortcuts: Layered cart totals (subtotal += item_price, subtotal -= discount_amount, subtotal *= (1 + tax_rate)).
Division of Work (3 People):
- Person 1 — Cart Input & Item Ledger:
- Ingests order data, calculates raw base totals, handles user membership flags and state tracking.
- Person 2 — Dynamic Discount & Coupon Rules Engine:
- Evaluates discount rules, bulk purchase thresholds, coupon conditions, and modulo-based freebie logic.
- **Person 3 — Fraud
=======

# Aprendendo Python
Codigos em ipynb para aprender
