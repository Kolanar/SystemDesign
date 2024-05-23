# Производительность

**Производительность** - это показатель того, насколько быстро и эффективно работает система. Кэширование, индексация и оптимизация запросов - это лишь некоторые из функций, повышающих производительность, которые должны быть включены в архитектуру.

**latency (задержка)**  - подразумевается время, которое требуется для передачи данных от одного устройства в сети к другому

**throughput** - пропускная способность

```mermaid
journey
	title Me studying for exams
	section Exam is announced
		I start studying: 1: Me
		Make notes: 2: Me
		Ask friend for help: 3: Me, Friend
		We study togther: 5: Me, Friend
	section Exam Day
		Syllabys is incomplete: 2: Me
		Give exam: 1: Me, Friend
	section Result Declared
		I passed the exam with destinction!: 5: Me
		Friend barely gets passing marks: 2: Friend
```

