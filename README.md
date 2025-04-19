# 🚀 REST API Flask – Lab

Prosty projekt API w Pythonie z użyciem Flask

## ✅ Wymagania

- Python 3.x
- Pip
- Flask

## ⚙️ Uruchomienie projektu

```bash
# Sklonuj repozytorium
git clone https://github.com/milosz013/rest-api-flask.git
cd rest-api-flask

---

# 1. (Opcjonalnie) Utwórz środowisko wirtualne
python -m venv venv
venv\Scripts\activate        # Windows
# lub
source venv/bin/activate    # Linux/macOS

# 2. Zainstaluj zależności
pip install -r requirements.txt

# 3. Uruchom aplikację
python app.py

---

## 🐳 Uruchamianie z użyciem Dockera (alternatywa)

Możesz uruchomić projekt również w kontenerze Docker bez instalowania Pythona lokalnie.

### 1. Zbuduj obraz Dockera:

```bash
docker build -t rest-api-flask .


# 2. Uruchom kontener
docker run -p 5000:5000 rest-api-flask

# 3. Sprawdź działanie w przeglądarce

http://localhost:5000/


# pomocniczy kod dodawania zmian do repo
git add .
git commit -m "Krótki opis zmiany"
git push