# Java Programming Assignment

This repository contains solutions to Java programming questions based on **Object-Oriented Programming, Exception Handling, Multithreading, Interfaces, and Java Collections**.

## 📚 Questions Overview

### Q1 — Spacecraft Fuel Calculation
Create a `Spacecraft` class with `distance` and `fuelEfficiency` data members. Calculate the required fuel using:

**Required Fuel = Distance / Fuel Efficiency**

If the fuel efficiency is `0`, handle the exception using `try-catch` and display **"Invalid fuel efficiency!"**.

**Concepts:** Classes, Objects, Methods, Exception Handling, `try-catch`

---

### Q2 — Artifact Tracker
Create a `LinkedList` to manage the names of rare artifacts displayed in a museum exhibition.

The program:
- Adds three artifacts.
- Adds a new artifact at the beginning.
- Removes an artifact.
- Displays the updated list.
- Displays the first and last artifacts.

**Concepts:** `LinkedList`, Adding Elements, Removing Elements, First/Last Element

---

### Q3 — Smart Parking System
Create a parking system using `Thread` where multiple vehicles try to book a limited number of parking slots.

A synchronized method ensures that two vehicles cannot incorrectly book the same available slot at the same time.

**Concepts:** Multithreading, `Thread`, `static synchronized`, Race Condition, Shared Resources

---

### Q4 — EV Vehicle Management
Create an `EVVehicle` class to manage electric vehicle information.

The program includes:
- Private vehicle details.
- Getter and setter methods.
- Parameterized constructor.
- Static vehicle counter.
- Final station name.
- Unique registration numbers.

**Concepts:** Encapsulation, Constructors, Getters/Setters, `static`, `final`, `HashSet`

---

### Q5 — Smart Home System
Create two interfaces:

- `SecuritySystem`
- `EnergySystem`

Create a `SmartHome` class that implements both interfaces and overrides their methods.

The program displays:

```text
Security is monitored
Energy check done
```

**Concepts:** Interfaces, Multiple Interface Implementation, Method Overriding

---

### Q6 — Online Shopping System
Create a `ProductDetails` class containing product ID, product name, and price.

Use an `ArrayList` to:
- Store product objects.
- Add three products.
- Display all products using a for-each loop.
- Remove one product.
- Display the updated product list.

**Concepts:** Classes, Constructors, Objects, `ArrayList`, For-Each Loop

---

### Q7 — College Event Registration
Create a collection to store names of students registered for a college technical event.

The collection must not allow duplicate student names.

The program:
- Adds at least four students.
- Displays the total number of students.
- Removes one student.
- Displays all registered students.

**Concepts:** `HashSet`, Collections, Duplicate Prevention, `size()`, `remove()`

---

### Q8 — Food Order Management
Create a `LinkedList` to manage food items selected by customers.

The program:
- Adds Pizza, Burger, Pasta, and Sandwich at the beginning of the list.
- Displays the first food item.
- Removes the last food item.
- Displays all remaining food items using a loop.

**Concepts:** `LinkedList`, `addFirst()`, `getFirst()`, `removeLast()`, For-Each Loop

---

## 🛠️ Technologies Used

- **Language:** Java
- **Collections:** `ArrayList`, `LinkedList`, `HashSet`
- **OOP Concepts:** Classes, Objects, Encapsulation, Constructors, Interfaces
- **Exception Handling:** `try-catch`
- **Multithreading:** `Thread`, Synchronization

## 📂 Repository Structure

```text
Java-Assignment/
│
├── Q1_Spacecraft/
│   └── Main.java
│
├── Q2_ArtifactTracker/
│   └── ArtifactTracker.java
│
├── Q3_ParkingArea/
│   └── Main.java
│
├── Q4_EVVehicle/
│   └── Main.java
│
├── Q5_SmartHome/
│   └── Main.java
│
├── Q6_ProductDetails/
│   └── Main.java
│
├── Q7_EventRegistration/
│   └── Main.java
│
├── Q8_FoodOrder/
│   └── FoodOrder.java
│
└── README.md
```

## 🎯 Purpose

This repository is created for practicing and demonstrating fundamental **Java programming and Object-Oriented Programming concepts** through real-world problem
