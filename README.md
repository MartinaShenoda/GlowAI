# **GlowAI**  

GlowAI is an AI-powered skincare and beauty recommendation app that helps you achieve radiant, healthy skin by providing personalized skincare routines, product recommendations, and ingredient insights. Using advanced image processing and machine learning technology, GlowAI analyzes your skin to create tailored solutions for your unique needs.

---

## **✨ Features**

- **AI-Powered Skin Analysis**  
  Upload a selfie, and GlowAI will analyze your skin to detect dryness, oiliness, acne, wrinkles, and other concerns. It uses cutting-edge machine learning models to determine your skin type and condition.

- **Personalized Skincare Routine**  
  Based on your skin analysis, GlowAI generates a customized morning and night skincare routine designed to target your unique needs, such as hydration, acne treatment, or anti-aging.

- **Product Recommendations**  
  Get personalized product recommendations based on your skin type and concerns. We suggest cleansers, moisturizers, serums, and more that are best suited for your skin.

- **Ingredient Insights**  
  Learn about the ingredients in your skincare products. GlowAI checks product labels for ingredients that are beneficial or harmful to your skin, helping you make informed decisions.

- **Save & Share Your Routine**  
  Save your skincare routines for easy access and share them with friends or on social media!

---

## **🚀 Tech Stack**

- **Frontend:** Angular  
- **Backend:** Django (for AI-driven logic)  
- **Database:** PostgreSQL  
- **AI Model:** TensorFlow + OpenCV (for skin analysis)  
- **Cloud Hosting:** AWS (EC2, S3 for image storage)  

---

## **📥 Getting Started**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/GlowAI.git
cd GlowAI
```

---

## **🔹 Backend Setup (Django)**

1. **Set Up Virtual Environment**  
   Create a virtual environment to isolate dependencies.

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install Dependencies**  
   Install the necessary Python packages.

   ```bash
   pip install django djangorestframework pillow tensorflow opencv-python psycopg2
   ```

3. **Configure PostgreSQL**  
   Update `settings.py` to configure your PostgreSQL database.

   ```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.postgresql',
           'NAME': 'skincare_db',
           'USER': 'your_user',
           'PASSWORD': 'your_password',
           'HOST': 'localhost',
           'PORT': '5432',
       }
   }
   ```

4. **Run Migrations**  
   Set up the database tables.

   ```bash
   python manage.py migrate
   ```

5. **Run the Server**  
   Start the Django server.

   ```bash
   python manage.py runserver
   ```

---

## **🔹 Frontend Setup (Angular)**

1. **Install Angular CLI**  
   If you don’t have Angular CLI installed yet, install it globally.

   ```bash
   npm install -g @angular/cli
   ```

2. **Install Frontend Dependencies**  
   Navigate to the `frontend` folder and install the necessary packages.

   ```bash
   npm install
   ```

3. **Run the Development Server**  
   Start the Angular development server.

   ```bash
   ng serve
   ```

   Your frontend will be running at **http://localhost:4200/**.

---

## **🔧 API Endpoints**

- **POST /api/upload/skin-analysis/**  
  Upload a selfie for AI skin analysis. The server will return your skin type and concerns.

- **GET /api/recommendations/**  
  Get personalized product recommendations based on your skin analysis.

- **GET /api/ingredients/**  
  Analyze the ingredients in a given skincare product and get insights.

---

## **💡 Contributing**

We welcome contributions to **GlowAI**! Here’s how you can help:

1. Fork the repo.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Submit a pull request with a detailed description.

---

## **📞 Contact**

- **Email:** martina.f.shenoda@gmail.com
- **Website:** [www.glowai.com](http://www.glowai.com) -- Coming soon...

---

## **🚀 Future Features**

- [ ] AI-Powered Skincare Chatbot  
- [ ] Community Reviews and Rating System  
- [ ] Integration with Online Stores (Sephora, Ulta)  
- [ ] Subscription Model for Premium Recommendations  
\
