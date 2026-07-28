# London Underground Network Analysis using NetworkX

## Project Overview

This project models a section of the **London Underground** transport network using Python and the **NetworkX** library. The network is represented as a weighted graph where:

- **Nodes** represent Underground stations.
- **Edges** represent railway connections between neighbouring stations.
- **Weights** represent the approximate distance (in kilometres) between connected stations.

The project demonstrates how graph theory can be applied to model and analyse a real-world transport network.

---

## Objectives

The project consists of three main tasks:

### Task 1 – Build a Small Underground Network

Create a simple graph consisting of five central London Underground stations:

- Oxford Circus
- Piccadilly Circus
- Leicester Square
- Covent Garden
- Charing Cross

Each station is connected using weighted edges representing the approximate distance between neighbouring stations.

---

### Task 2 – Extend the Network

Expand the network to include additional Underground stations and railway connections.

The final network contains:

- **21 stations**
- Multiple Underground lines including:
  - Bakerloo Line
  - Piccadilly Line
  - Northern Line
  - Central Line
  - Jubilee Line

The extended graph provides a more realistic representation of the London Underground system.

---

### Task 3 – Network Statistics

Calculate several statistics for the completed graph, including:

- Number of stations
- Number of railway connections
- Total network length
- Average connection distance
- Standard deviation of connection distances

These statistics provide insight into the overall structure of the transport network.

---

## Technologies Used

- Python 3
- NetworkX
- NumPy
- Pandas
- Matplotlib

---

## Project Structure

```
main.ipynb
README.md
```

- **main.ipynb** – Jupyter Notebook containing all code for graph construction, visualisation, and network analysis.
- **README.md** – Project documentation.

---

## Installation

Install the required Python packages:

```bash
pip install networkx matplotlib numpy pandas
```

---

## Running the Project

Open the notebook:

```bash
jupyter notebook main.ipynb
```

or

```bash
jupyter lab
```

Run all cells to:

1. Build the Underground graph.
2. Visualise the network.
3. Calculate network statistics.

---

## Example Output

The notebook calculates statistics such as:

- Number of stations
- Number of railway connections
- Total network length (km)
- Average connection distance
- Standard deviation of edge distances

---

## Graph Representation

The transport network is represented as an undirected weighted graph:

- **Nodes:** Underground stations
- **Edges:** Railway connections
- **Weights:** Distance between stations (km)

This representation allows graph algorithms and statistical analysis to be applied efficiently.

---

## Author

**Le Hoang Huu Phuc**

---

## License

This project was developed for academic coursework purposes.