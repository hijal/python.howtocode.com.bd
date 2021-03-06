## আরও কিছু নিউমেরিক অপারেশন

যোগ, বিয়োগ, গুন ভাগ বাদেও পাইথনে **এক্সপনেন্সিয়েশন** এর সাপোর্ট আছে যাকে আমরা একটি সংখ্যার উপর আরেকটা সংখ্যার পাওয়ার বলে থাকি। দুটো ** চিহ্ন দিয়ে এই অপারেশন করা হয়। যেমন -

```python
>>> 2 ** 3
8
>>> 3 ** 3
27
```

শুধুমাত্র **ভাগফল** (quotient) নির্ণয়ের জন্য ```floor division``` এবং **ভাগশেষ** নির্ণয়ের জন্য ```modulo operator``` ব্যবহার করা হয়। দুটো ফরওয়ার্ড স্ল্যাস ```//``` ব্যবহার করে ```floor division``` করা হয় আর ```%``` সিম্বল দিয়ে ```modulo operator``` এর কাজ করা হয়। নিচের উদাহরণটি দেখি -

```python
>>> 10 // 3
3
>>> 10 % 3
1
```

এখানে ৩ দিয়ে ১০ কে ভাগ করলে পূর্ণ ভাগফল আসে ৩ এবং ১০ কে ৩ দিয়ে ভাগ করলে ভাগশেষ থাকে ১
