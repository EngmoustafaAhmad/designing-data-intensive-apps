<div dir="rtl">

# 📘 سلسلة Designing Data-Intensive Applications – الملخص الكامل

---

## 📚 Part I – Foundations

### 1️⃣ Reliable, Scalable, Maintainable Applications
- نظم التطبيقات لتكون **موثوقة**، **قابلة للتوسع**، و**سهلة الصيانة**  
- أدوات: Replication, Backups, Modular Design, CI/CD

### 2️⃣ Data Models and Query Languages
- اختيار نموذج البيانات الصحيح مهم  
- Relational, Document, Graph  
- SQL vs NoSQL  
- Trade-offs في الأداء والمرونة

### 3️⃣ Storage and Retrieval
- كيف تخزن البيانات بكفاءة  
- Storage Engines: LSM-trees, B-trees  
- Indexing, Caching, Compaction  

---

## 📚 Part II – Distributed Data

### 4️⃣ Data Encoding and Evolution
- إدارة تطور البيانات والتوافق بين النسخ  
- Formats: JSON, Avro, Protobuf  
- Schema evolution

### 5️⃣ Replication
- نسخ البيانات على سيرفرات متعددة  
- Leader-Follower, Multi-Leader, Leaderless  
- التحديات: Replication Lag, Consistency Models

### 6️⃣ Partitioning (Sharding)
- تقسيم البيانات لتقليل الضغط على سيرفر واحد  
- Strategies: Range, Hash, Directory-based  
- تحديات: Hotspots, Rebalancing

### 7️⃣ Transactions
- ضمان Atomicity وConsistency وIsolation  
- ACID vs BASE  
- Two-Phase Commit, Optimistic vs Pessimistic Concurrency

### 8️⃣ The Trouble with Distributed Systems
- الشبكة غير موثوقة  
- Partial failures صعبة الاكتشاف  
- CAP Theorem: Consistency, Availability, Partition tolerance  

### 9️⃣ Consistency and Consensus
- كل Node يتفق على نفس القرار  
- Paxos, Raft  
- Linearizability, Eventual Consistency  
- Two-Phase Commit

---

## 📚 Part III – Derived Data

### 10️⃣ Batch Processing
- معالجة البيانات على دفعات كبيرة  
- MapReduce, Data Pipelines  
- Immutable data, High throughput, Cost-efficient

### 11️⃣ Stream Processing
- معالجة البيانات فور وصولها (Real-time)  
- Stateful Stream Processing  
- Event time vs Processing time  
- Latency, Fault tolerance, Scaling

### 12️⃣ The Future of Data Systems
- توحيد Batch و Stream  
- Separation of Storage & Compute  
- Unbundling Databases  
- Cloud-native architectures  
- اختيار Trade-offs بشكل ذكي  

---

## 💡 الفكرة الذهبية للسلسلة

الهندسة ليست عن الكمال، بل عن **إدارة التعقيدات والتنازلات**:

- توقع الفشل  
- اختيار الأدوات الصحيحة  
- إدارة الاتساق مقابل الأداء  
- تصميم النظام كـ **كيان متكامل** وليس مجرد قاعدة بيانات  

---

## 🚀 لمن هذه السلسلة؟

- Backend Developers  
- Data Engineers  
- Cloud Architects  
- SaaS Engineers  
- أي مهندس يريد فهم الأنظمة الموزعة بشكل عميق  

---

</div>
