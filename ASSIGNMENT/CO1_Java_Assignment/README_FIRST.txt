TASK 10 – PACKAGES AND ENCAPSULATION
------------------------------------
Folder: Task10_Packages_Encapsulation

The source files use packages:
  parking.model
  parking.service
  parking.app

From inside Task10_Packages_Encapsulation:
  javac -d out src/parking/model/ParkingSlot.java src/parking/model/ParkingTicket.java src/parking/service/ParkingService.java src/parking/app/Task10Demo.java
  java -cp out parking.app.Task10Demo

Expected result is recorded in Task10_Packages_Encapsulation/EXPECTED_OUTPUT.txt.

TASK 11 – IMPLEMENT, TEST AND DEFEND THE DESIGN
------------------------------------------------
Folder: Task11_Implementation_Testing

From inside Task11_Implementation_Testing:
  javac ParkingSystemDemo.java
  java ParkingSystemDemo

The program runs normal, boundary and invalid-input tests, then calculates and prints
a small day's collection. It uses an array of active tickets as the baseline structure.
Expected result is recorded in EXPECTED_OUTPUT.txt.

TASK 12 – RE-EVALUATE AND ADAPT THE DESIGN
------------------------------------------
Folder: Task12_Design_Challenge

From inside Task12_Design_Challenge:
  javac DesignChallengeDemo.java
  java DesignChallengeDemo

The program demonstrates:
- e-bikes with a flat parking fee
- delivery vans at double the car rate during 09:00–17:00
- a one-day visitor pass
- five floors with unequal slot counts using a jagged array
- a pricing-rule abstraction and evidence-based test output

Expected result is recorded in EXPECTED_OUTPUT.txt.

