# 🚦 Shortest Path Finder

A **web-based visualization project** that demonstrates **Dijkstra’s Algorithm** using **real road map data**.  
Users can select two points on a map and visually see how the **shortest path** is found.

---

## 📌 What This Project Does

- Select **start** and **destination** on a map
- Fetch **real routes** using MapQuest API
- Convert routes into a **graph**
- Apply **Dijkstra’s Algorithm**
- Animate how the **shortest path** is discovered
- Display distance, time, and explored nodes

---

## 🧠 What Is Dijkstra’s Algorithm?

Dijkstra’s Algorithm finds the **shortest path** between two nodes in a **weighted graph**.

**How it works:**
1. Start from source node
2. Pick the unvisited node with smallest distance
3. Update neighboring node distances
4. Repeat until destination is reached

Used in **GPS systems, maps, and network routing**.

---

## 🗺️ How This Project Uses Dijkstra

- Roads → edges  
- Intersections → nodes  
- Distance/time → edge weights  

Multiple real routes are merged into one graph, and Dijkstra selects the **optimal path** which is then highlighted on the map.

---

## ▶️ How to Run

1. Download or clone the repository  
2. Open `main.html` in a browser  
3. Project runs instantly (no setup required)

---

## 🧭 How to Use

1. Enable route selection  
2. Click map to choose start & end  
3. Select travel mode  
4. Fetch routes  
5. Visualize Dijkstra

---

## 🎥 Visualization Guide

- 🟢 Start node  
- 🔴 End node  
- 🟡 Exploring node  
- 🟩 Final shortest path  

Steps are shown live during execution.

---

## 🧪 Technologies Used

- HTML, CSS, JavaScript  
- Leaflet.js  
- MapQuest Directions API  
- Python (reference implementation)

---

## 🎓 Use Case

- Algorithm visualization  
- Dijkstra learning aid  
- University / academic project

---

## Group Members
- **Subhan Ahmad (BSDSF24M048)**
- **Faizan Aslam Bhatti (BSDSF24M051)**
- **Muhammad Akmal (BSDSF24M059)**
