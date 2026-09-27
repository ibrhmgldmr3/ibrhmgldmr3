<h1 align="center">Merhaba, ben İbrahim Güldemir 👋</h1>

<p align="center">
Bilgisayar Mühendisi · Sakarya Üniversitesi<br/>
Yapay Zeka · Bilgisayarlı Görü · Veri Mühendisliği · Full-Stack
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ibrhmgldmr/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ibrahimguldemir123@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.instagram.com/ibrhmgldmr/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>

---

## 🚀 Hakkımda

Sakarya Üniversitesi Bilgisayar Mühendisliği bölümünden mezun oldum. 
Yapay zeka, makine öğrenmesi, bilgisayarlı görü ve gerçek zamanlı veri sistemleri üzerine uçtan uca projeler geliştiriyorum: veri hazırlığından model eğitimine, değerlendirmeden API ve arayüzle servis etmeye kadar.

---

## 🎯 Şu An Üzerinde Çalıştıklarım

- 🎸 **AI Music Transcriber** *(repo yakında)* — Gitar kayıtlarını nota, MIDI ve gitar TAB'ına dönüştüren uçtan uca otomatik müzik transkripsiyonu sistemi. Notaları CNN + BiLSTM modeli tespit ediyor; hangi tel ve perdede çalınacağına tab kafalı bir model ile Viterbi tabanlı bir parmak yolu optimizer'ı birlikte karar veriyor. GuitarSet testinde nota F1 **0.90**, tel/perde isabeti **0.95**. Sonuçlar TAB, piyano rulosu ve nota görünümü olan bir müzik editöründe düzenlenip MIDI/MusicXML olarak dışa aktarılabiliyor. *PyTorch · FastAPI · Celery · Next.js*
- 📺 **[Make A Playlist](https://github.com/ibrhmgldmr3/LLM-AGENT-PlaylistMaker)** — Playlist oluşturucuyu, videolar ve belgeler üzerinden kaynak göstererek cevap veren RAG destekli bir öğrenme platformuna dönüştürüyorum.
- 🚌 **[GTFS Service](https://github.com/ibrhmgldmr3/gtfs_service_1)** — Kullanıcı hesaplarıyla herkesin kendi GTFS ve akıllı kart verisini yükleyip analiz edebileceği bir toplu taşıma analiz platformuna dönüştürüyorum.
- 🥫 **macroLLM** — Paketli gıda etiketlerinden besin değerlerini çıkaran OCR + LLM sistemi (PaddleOCR, QLoRA ile fine-tune edilmiş Qwen2.5). vLLM ile servis edilip, kullanıcıların tükettikleri paketli gıdaları takip edebildiği bir uygulamaya dönüşecek.
- ✈️ **[Trip Planner](https://github.com/ibrhmgldmr3/Trip-Planner)** — Maliyet ve mesafe hesaplarını iyileştirip yayına almaya hazırlıyorum.

---

## 🧩 Öne Çıkan Projeler

**👁️ Bilgisayarlı Görü**

| Proje | Açıklama | Teknolojiler |
|---|---|---|
| [**Türk Plaka Tanıma (ANPR)**](https://github.com/ibrhmgldmr3/turkish-anpr) | Uçtan uca plaka tespiti + OCR + Türk plaka formatına özel düzeltme katmanı. Tespitte mAP50 **0.99**, uçtan uca **~25 FPS** | YOLOv8, EasyOCR, OpenCV, Streamlit |
| [**Endüstriyel Kusur Segmentasyonu**](https://github.com/ibrhmgldmr3/defect-segmentation) | MVTec AD üzerinde piksel seviyesinde kusur segmentasyonu; U-Net ve DeepLabV3+ karşılaştırması, Grad-CAM ile açıklanabilirlik | PyTorch, U-Net, DeepLabV3+ |
| [**CLIP Görsel Arama Motoru**](https://github.com/ibrhmgldmr3/clip-visual-search) | Doğal dil sorgusuyla 10.000 görsel içinde arama; ek olarak ResNet50 ve ViT-Small karşılaştırması (CIFAR-10'da %86.6'ya karşı **%97.4**) | CLIP, FAISS, timm, Grad-CAM |
| [**Simpsons Character X-Ray**](https://github.com/ibrhmgldmr3/simpsons-character-xray) | Videoda karakterleri tespit edip kare bazında etiketleyen detection + classification pipeline'ı, XAI analizleri | YOLO, TensorFlow, PyTorch, DINOv2 |
| [**YOLOv8 Detection & Segmentation**](https://github.com/ibrhmgldmr3/yolov8_seg) | Veri setinden bağımsız eğitim, Optuna ile HPO, ONNX/TensorRT export ve latency benchmark'ı | YOLOv8, Optuna, FastAPI, Gradio |

**🤖 LLM & RAG**

| Proje | Açıklama | Teknolojiler |
|---|---|---|
| [**Make A Playlist**](https://github.com/ibrhmgldmr3/LLM-AGENT-PlaylistMaker) | Bir öğrenme hedefini sıralı bir YouTube oynatma listesine çeviriyor; videolar ve belgeler üzerinden saniyesine kadar kaynak gösteren soru-cevap | Gemini, FastAPI, React, Redis, Docker |
| [**RAG Document Assistant**](https://github.com/ibrhmgldmr3/rag_systems) | PDF koleksiyonları için kaynak gösterimli soru-cevap; hibrit retrieval, reranking ve guardrail'ler | FAISS, BM25, Transformers, FastAPI |

**📡 Veri Mühendisliği & Full-Stack**

| Proje | Açıklama | Teknolojiler |
|---|---|---|
| [**GTFS Service**](https://github.com/ibrhmgldmr3/gtfs_service_1) | Planlanan toplu taşıma tarifesini akıllı kart verisiyle eşleştirip dakiklik ve kümelenme (bunching) analizi yapan servis | FastAPI, PostgreSQL, Celery, Airflow, RabbitMQ, React |
| [**IoT Veri Akışı Simülasyonu**](https://github.com/ibrhmgldmr3/IOT_Based_Data_Flow_Simulation) | Config tabanlı gerçek zamanlı büyük veri pipeline'ı: sensör verisi → Kafka → Spark Streaming → MongoDB | Kafka, Spark, MongoDB, Docker |
| [**Trip Planner**](https://github.com/ibrhmgldmr3/Trip-Planner) | Stajda geliştirdiğim AI destekli seyahat planlama ve bütçe yönetimi platformu | Next.js, TypeScript, Prisma, NextAuth |

---

## 🛠️ Teknoloji Yığını

**Diller**

![Python](https://img.shields.io/badge/Python-333333?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-333333?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-333333?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-333333?style=for-the-badge&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-333333?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-333333?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-333333?style=for-the-badge&logo=mysql&logoColor=white)

**Yapay Zeka & Bilgisayarlı Görü**

![PyTorch](https://img.shields.io/badge/PyTorch-333333?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-333333?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-333333?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-333333?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-333333?style=for-the-badge&logo=huggingface&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-333333?style=for-the-badge&logo=langchain&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-333333?style=for-the-badge&logo=streamlit&logoColor=white)

**Veri & Altyapı**

![FastAPI](https://img.shields.io/badge/FastAPI-333333?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-333333?style=for-the-badge&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-333333?style=for-the-badge&logo=apachekafka&logoColor=white)
![Spark Streaming](https://img.shields.io/badge/Spark_Streaming-333333?style=for-the-badge&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-333333?style=for-the-badge&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-333333?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-333333?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-333333?style=for-the-badge&logo=redis&logoColor=white)

**Web Geliştirme**

![React](https://img.shields.io/badge/React-333333?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-333333?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-333333?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-333333?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-333333?style=for-the-badge&logo=prisma&logoColor=white)

---

## 📊 GitHub İstatistikleri

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ibrhmgldmr3&theme=dracula" height="165" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ibrhmgldmr3&theme=dracula" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ibrhmgldmr3&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" height="165" />
</p>

---

## 🌱 Öğrenme Yol Haritam

- İleri düzey makine öğrenmesi ve derin öğrenme
- Bilgisayarlı görü modellerinin production'a alınması (ONNX / TensorRT, servisleştirme)
- Ses ve müzik sinyal işleme (otomatik müzik transkripsiyonu)
- Gerçek zamanlı veri işleme sistemleri
- Bulut tabanlı backend mimarileri
- LLM tabanlı uygulama tasarımı

---

<p align="center">
  <a href="https://www.linkedin.com/in/ibrhmgldmr/">LinkedIn</a> ·
  <a href="mailto:ibrahimguldemir123@gmail.com">E-posta</a> ·
  <a href="https://www.instagram.com/ibrhmgldmr/">Instagram</a>
</p>
