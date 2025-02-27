# 🔥 FLAMES - Personalized Fashion Recommendation System 🔥

## Outfit Lab

### 👗 Want a personal stylist for your wardrobe? 👔 We've got you covered!

## Team Members
- Dr. Premjith B
- Harish Vijay V
- Amrit Subramanian
- Ippatapu Venkata Srichandra
- Pathange Omkareshwara Rao

---

## Introduction
FLAMES is a **personalized fashion recommendation system** designed to help users choose outfits based on their wardrobe and event preferences. The system leverages AI models and advanced database solutions to provide intelligent fashion recommendations.

### **🛠️ **Key Components:****
- **FastAPI** (Backend API)
- **Firebase** (Image Storage)
- **Qdrant VectorDB** (Efficient Embedding Storage)
- **CLIP Model** (Image Embedding)
- **Neo4j GraphDB** (Wardrobe Organization)
- **FashionGAN** (Outfit Visualization)

---

## 📝 **Workflow**
<img src="Outfit Lab/Workflow/OutfitLab.png" alt="Workflow" width="100%">
### **Step 1: User Input and Wardrobe Access**
- Users upload images of clothing, accessories, and body images.
- Images are captured with clear views of attire, watches, jewelry, etc.
- FastAPI handles image uploads and sends them to the backend.

### **Step 2: Uploading Images to Firebase**
- Images are stored securely in Firebase Cloud Storage, organized by user IDs.
- Firebase ensures secure access and easy retrieval of wardrobe images.

### **Step 3: Embedding Creation Using CLIP Model**
- Images are converted into embeddings (vector representations) using the **CLIP model**.
- These embeddings combine image and text descriptions for better recommendations.

### **Step 4: Embedding Storage in Qdrant VectorDB**
- The generated embeddings are stored in **Qdrant VectorDB**, allowing fast, scalable access.

### **Step 5: Image Classification Using Gemini Groq**
- Images are classified into categories like shirts, pants, watches, etc.
- The classification helps in organizing the wardrobe effectively.

### **Step 6: Storage in Neo4j GraphDB**
- Items are stored in **Neo4j Graph Database** under respective categories.
- The knowledge graph enables structured wardrobe organization and better recommendations.

### **Step 7: User Occasion Input and Query Handling**
- Users specify the occasion (e.g., wedding, party) and outfit preferences.
- The text input is converted into embeddings and stored in **MongoDB Atlas**.

### **Step 8: Ensemble Scoring for Recommendations**
- Outfit recommendations are generated based on ensemble scoring of **image and text embeddings**.
- This ensures the best match based on user preferences.

### **Step 9: Visualization with FashionGAN**
- Selected outfits are sent to **FashionGAN** to generate a visualization of how they look.

### **Step 10: Final Attire Recommendations**
- The user receives **attire and accessory combinations** with visual references.

---

## 📊 **Initial Results**
✅ **Image Upload & Storage**
- Users can upload wardrobe images using FastAPI.
- Firebase securely stores images for efficient media management.

✅ **Embedding Generation**
- Images are processed using the **CLIP embedding model** to extract key features like color, texture, and style.

✅ **Efficient Embedding Storage**
- Qdrant VectorDB allows **fast and efficient retrieval** of image embeddings.

✅ **Image Classification**
- Integrated **Gemini Groq** to classify wardrobe items like shirts, pants, watches, and accessories.

✅ **Knowledge Graph Management**
- Built a **Neo4j Knowledge Graph** to categorize wardrobe items for structured recommendations.

---

## 🛠️ **Yet-To-Do**
🔹 **Backend Efficiency Optimization**
- Improve storage performance and enhance data pipelines for faster processing.

🔹 **Knowledge Graph Improvement**
- Enhance Neo4j graph relationships for more intuitive outfit recommendations.

🔹 **Accessory Recommendations Enhancement**
- Improve classification and recommendation of watches, belts, jewelry, etc.

---

## 🙏 **Thank You!** 🎉 🎉
This project aims to **redefine fashion recommendations** using AI-driven insights. Stay tuned for updates!
