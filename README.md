# CSA09 Assignment 1: Campus Smart-Parking System

- **Name:** Bala Ashwin R
- **Register number:** 1921260102
- **Java version:** OpenJDK 21 (replace with the output of `java -version` on your machine)

## How to compile and run
Open a terminal inside a task folder, then:
```
javac *.java
java <MainClass>
```

| Task | Main class | Result |
|---|---|---|
| Task01 | `ParallelArraysDemo` | Candidate classes, business rules and assumptions are in the report. Parallel arrays and objects both find a vehicle in O(n); objects make adding an attribute a one-place change. |
| Task02 | `CastingDemo` | (130/60)*30 gives Rs 60 (wrong); (130+59)/60*30 gives Rs 90 (correct). Jagged array supports uneven floors. |
| Task03 | `ParkingFacility` | Output matches the expected output exactly: [0, 0] [0, 1] [1, 0] null / true false false / [0, 1]. |
| Task04 | `ConstructorDemo` | Chaining with this(...) and a copy constructor that re-issues the same ticket number. |
| Task05 | `StaticCounterDemo` | An instance counter gives both facilities ticket 1; a static counter keeps ticket numbers unique. |
| Task06 | `ConstructorOrderDemo` | Constructor bodies run Vehicle, then Car, then ElectricCar. UML diagram is in the report. |
| Task07 | `OverrideDemo` | Car and EV with the same plate are equal, have equal hash codes and collapse to one HashSet entry. |
| Task08 | `FeeDemo` | Output matches expected: Rs 30.0, Rs 90.0, Rs 210.0, true. |
| Task09 | `AbstractionDemo` | Abstract class for shared state, interfaces for capabilities; default and static interface methods demonstrated. |
| Task10 | `EncapsulationDemo` | Validating setter rejects -5; Integer 1000 == 1000 is false but equals() is true. |
| Task11 | `Task11Main` | 15 of 15 tests pass; hand-calculated daily collection Rs 270 equals the program output. |
| Task12 | `Task12Main` | Decision MODIFY. 15 regression tests plus 7 new tests pass; daily collection Rs 380 matches the hand calculation. |

The full report with UML diagram, pseudocode, complexity analyses and test tables is `CSA09-1921260102-Assignment1-Report.pdf`.
