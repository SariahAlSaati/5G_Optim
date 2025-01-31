# Optimization of user scheduling for 5G network


## 📌 Overview  
This repository contains the code for the resolution of a user scheduling optimization problem developed as part of an **algorithm design and optimization class** during my second year of engineering studies at École polytechnique. The code was co-developed with my colleague Youssef A. 

#
## 🧮 How to

### **Preprocessing**  
**Arguments:** `String[] path`, `boolean display` (default = `false`)  

**Output:** Returns the preprocessing results of the file located at `path`. The boolean `display` allows requesting the display of `Xnkm` tables after preprocessing.  

**Example:**  
```
java Preprocessing ../testfiles/test1.txt true
```

---

### **Dynamic Programming**  
**Arguments:** `String[] path`, `boolean display` (default = `false`)  

**Output:** Returns the results after applying `DynamicProgramming` algorithm to the file located at `path`. The boolean `display` allows requesting the display of `Xnkm` tables after processing.  

**Example:**  
```
java DynamicPrograming ../testfiles/test1.txt true
```

---

### **Greedy**  
**Arguments:** `String[] path`, `boolean display` (default = `false`)  

**Output:** Returns the results after applying the `Greedy` algorithm program to the file located at `path`. The boolean `display` allows requesting the display of `Xnkm` tables after processing.  

**Example:**  
```
java Greedy ../testfiles/test1.txt true
```

---

### **Online**  
**Arguments:** `int iterations` (default = `10,000`)  

**Output:** Returns the results obtained after applying the `Online` algorithm over a given number of `iterations`. These results are compared with the greedy algorithm applied to the same problem after all users have been generated.  

**Example:**  
```
java Online 1000000
```

---

### **Online2**  
**Arguments:** `int iterations` (default = `10,000`)  

**Output:** Returns the results obtained after applying the `Online2` algorithm over a given number of `iterations`. These results are compared with the greedy algorithm applied to the same problem after all users have been generated.  

**Example:**  
```
java Online2 1000000
```

---

### **Online3**  
**Arguments:** `int iterations` (default = `10,000`)  

**Output:** Returns the results obtained after applying the `Online3` algorithm over a given number of `iterations`. These results are compared with the greedy algorithm applied to the same problem after all users have been generated.  

**Example:**  
```
java Online3 1000000
```
