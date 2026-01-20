Ride Booking System (Java Console Application)

 * Project Overview
This is a console-based Ride Booking System developed in Java.  
The application allows riders to request rides, matches them with available drivers using pluggable strategies, calculates fares using flexible pricing strategies, and tracks ride status throughout its lifecycle.

The project is designed using clean architecture principles with a strong focus on **low coupling**, **maintainability**, and **extensibility**.

---

# Features
- Register riders and drivers
- View available drivers
- Request a ride
- Driver matching using strategy pattern
- Fare calculation using pricing strategies
- Track ride status:
  - REQUESTED
  - ASSIGNED
  - COMPLETED
  - CANCELLED
- Console-based interactive menu



# Tech Stack
- Java (Core Java)
- OOP Principles
- Strategy Design Pattern
- Clean Architecture
- Console Application



# Design Principles Used
- Strategy Pattern for driver matching and fare calculation
- Dependency Inversion Principle (DIP)
- Open/Closed Principle (OCP)
- Composition over Inheritance
- Low Coupling & High Cohesion



# How to Run
1. Clone the repository
   bash
   git clone <repository-url>



## 📂 Project Structure

```text
ridebooking/
├── Main.java
│
├── model/
│   ├── Rider.java
│   ├── Driver.java
│   ├── Ride.java
│   ├── FareReceipt.java
│   ├── RideStatus.java
│   └── VehicleType.java
│
├── service/
│   ├── RiderService.java
│   ├── DriverService.java
│   └── RideService.java
│
├── strategy/
│   ├── RideMatchingStrategy.java
│   ├── NearestDriverStrategy.java
│   ├── LeastActiveDriverStrategy.java
│   ├── FareStrategy.java
│   ├── DefaultFareStrategy.java
│   └── PeakHourFareStrategy.java

