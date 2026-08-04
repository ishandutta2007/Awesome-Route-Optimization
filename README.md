<div align="center">
  <img src="assets/banner.svg" alt="Awesome Route Optimization Banner" />
</div>
<br/>
<div align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</div>

# Awesome Route Optimization Platforms 🚀

**Route Optimization Platforms** help businesses plan efficient multi-stop routes for delivery, field service, and logistics fleets. They solve Vehicle Routing Problems (VRP) with constraints such as time windows, vehicle capacity, driver shifts, and traffic, while providing dispatching, tracking, and analytics. Leading commercial platforms include OptimoRoute, Routific, Route4Me, Onfleet, Circuit, NextBillion.ai, FarEye, LogiNext, MyRouteOnline, and Badger Maps.

## 🎯 What is Route Optimization? (SEO)
Route optimization is the process of discovering the most cost-effective route for a fleet of vehicles. It involves complex algorithmic planning to solve the Vehicle Routing Problem (VRP) and Traveling Salesperson Problem (TSP), maximizing operational efficiency, minimizing fuel costs, and improving on-time deliveries.

Below is a **curated list** of notable platforms and their open-source equivalents. The open-source ecosystem for routing and vehicle routing optimization is quite mature, especially at the engine and solver level.

## 🏢 SaaS / Hosted Platforms 🌐

| Product | Description | Pricing | Free Tier Limit | Company Size (Valuation/Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| **[Route4Me](https://www.route4me.com/)** | Comprehensive route planning and optimization platform with mobile apps and territory management. | ~$300/month | 7-day free trial | ~$1B+ Valuation |
| **[FarEye](https://fareye.com/)** | Enterprise-grade intelligent delivery management platform. | Custom Pricing | N/A | ~$100M+ Valuation |
| **[NextBillion.ai](https://www.nextbillion.ai/)** | Specialized route optimization platform for enterprise scaling. | Custom Pricing | N/A | ~$100M+ Valuation |
| **[Onfleet](https://onfleet.com/)** | Last-mile delivery management platform with routing, dispatch, and real-time tracking. | ~$550/month | 14-day free trial | ~$50M+ Valuation |
| **[LogiNext](https://www.loginextsolutions.com/)** | Logistics automation and field service management. | Custom Pricing | N/A | ~$50M+ Valuation |
| **[OptimoRoute](https://optimoroute.com/)** | Popular route optimization and dispatch platform for delivery and field service teams. | ~$39/driver/month | 30-day free trial | ~$10M+ Revenue |
| **[Routific](https://www.routific.com/)** | Route optimization software focused on last-mile delivery planning. | ~$49/vehicle/month | 7-day free trial | ~$10M+ Revenue |
| **[Circuit](https://getcircuit.com/)** | Route optimization app popular with small delivery and service businesses. | ~$20/driver/month | Free up to 10 stops/route | ~$10M+ Revenue |
| **[Badger Maps](https://www.badgermaps.com/)** | Specialized route planning and mapping software for field sales reps. | ~$58/user/month | 7-day free trial | ~$5M+ Revenue |
| **[MyRouteOnline](https://www.myrouteonline.com/)** | Route optimization software utilizing a credit system. | Starts at ~$29.95/month | Trial credits only | ~$2M+ Revenue |

## 🔓 Open-Source Software 💻

### 🚚 Vehicle Routing Problem (VRP) Solvers & Routing Engines

| Project | Description | Stars |
| :--- | :--- | :--- |
| **[OR-Tools](https://github.com/google/or-tools)** | Google's fast and portable software suite for combinatorial optimization problems, including a very powerful Vehicle Routing solver. | [![GitHub Repo stars](https://img.shields.io/github/stars/google/or-tools?style=social&color=white)](https://github.com/google/or-tools/stargazers) |
| **[OSRM (Open Source Routing Machine)](https://github.com/Project-OSRM/osrm-backend)** | High-performance routing engine for shortest/fastest paths, turn-by-turn directions, and table/matrix services on OpenStreetMap data. | [![GitHub Repo stars](https://img.shields.io/github/stars/Project-OSRM/osrm-backend?style=social&color=white)](https://github.com/Project-OSRM/osrm-backend/stargazers) |
| **[GraphHopper](https://github.com/graphhopper/graphhopper)** | Fast, memory-efficient open-source routing engine based on OpenStreetMap data. Supports route calculation, isochrones, matrix requests, and can be self-hosted or used via API. | [![GitHub Repo stars](https://img.shields.io/github/stars/graphhopper/graphhopper?style=social&color=white)](https://github.com/graphhopper/graphhopper/stargazers) |
| **[Valhalla](https://github.com/valhalla/valhalla)** | Flexible open-source routing engine with strong support for multiple costing models and time-dependent routing. | [![GitHub Repo stars](https://img.shields.io/github/stars/valhalla/valhalla?style=social&color=white)](https://github.com/valhalla/valhalla/stargazers) |
| **[Jsprit](https://github.com/graphhopper/jsprit)** | Java-based, lightweight vehicle routing problem solver capable of handling rich VRPs. | [![GitHub Repo stars](https://img.shields.io/github/stars/graphhopper/jsprit?style=social&color=white)](https://github.com/graphhopper/jsprit/stargazers) |
| **[Timefold Solver](https://github.com/TimefoldAI/timefold-solver)** | AI constraint solver in Java that optimizes vehicle routing, employee rostering, and maintenance scheduling (formerly OptaPlanner). | [![GitHub Repo stars](https://img.shields.io/github/stars/TimefoldAI/timefold-solver?style=social&color=white)](https://github.com/TimefoldAI/timefold-solver/stargazers) |
| **[pgRouting](https://github.com/pgRouting/pgrouting)** | Open-source routing extension for PostGIS/PostgreSQL, ideal for teams already using spatial databases. | [![GitHub Repo stars](https://img.shields.io/github/stars/pgRouting/pgrouting?style=social&color=white)](https://github.com/pgRouting/pgrouting/stargazers) |
| **[VROOM](https://github.com/VROOM-Project/vroom)** | Vehicle Routing Open-source Optimization Machine. High-performance C++ solver that handles TSP, CVRP, VRPTW, multi-depot, and pickup-and-delivery problems in milliseconds. | [![GitHub Repo stars](https://img.shields.io/github/stars/VROOM-Project/vroom?style=social&color=white)](https://github.com/VROOM-Project/vroom/stargazers) |
| **[OpenRouteService](https://github.com/GIScience/openrouteservice)** | Open-source routing service built on OpenStreetMap that provides directions, isochrones, matrices, and optimization endpoints. | [![GitHub Repo stars](https://img.shields.io/github/stars/GIScience/openrouteservice?style=social&color=white)](https://github.com/GIScience/openrouteservice/stargazers) |
| **[PyVRP](https://github.com/PyVRP/PyVRP)** | State-of-the-art open-source VRP solver available as an easy-to-use Python package. Supports capacitated VRP, time windows, heterogeneous fleets, pickups & deliveries, and more. | [![GitHub Repo stars](https://img.shields.io/github/stars/PyVRP/PyVRP?style=social&color=white)](https://github.com/PyVRP/PyVRP/stargazers) |
| **[routingpy](https://github.com/gisops/routingpy)** | One Python library to access multiple routing engines (OSRM, Valhalla, GraphHopper, ORS, etc.). | [![GitHub Repo stars](https://img.shields.io/github/stars/gisops/routingpy?style=social&color=white)](https://github.com/gisops/routingpy/stargazers) |

### 🌍 Fleet & Route Optimization Platforms
- Open-source fleet management and route optimizer projects that combine VRP solvers with web dashboards, GPS tracking, and dispatch features (search GitHub for “fleet route optimizer” or similar).
- Tools that integrate VROOM or PyVRP with mapping front-ends for end-to-end route planning.

### 🛠️ Typical Open-Source Approach
1. **Routing engine** — OSRM, GraphHopper, or Valhalla for accurate travel times and distances
2. **Optimization solver** — VROOM or PyVRP for multi-stop vehicle routing with real constraints
3. **Frontend / Dispatch** — Custom web app or existing open-source fleet dashboards
4. **Maps & geocoding** — OpenStreetMap + Nominatim or self-hosted alternatives
5. **Tracking** — Optional real-time GPS integration

This stack allows teams to build fully self-hosted route optimization systems with no per-vehicle or per-route licensing fees, full data ownership, and the ability to customize algorithms for specific business rules.

---

## 🤝 How to contribute  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to route optimization, vehicle routing problems (VRP), last-mile delivery, or open routing engines.

## 📄 License  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open routing tools help logistics and field teams deliver more efficiently without proprietary lock-in! 🚚

## 📈 Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Route-Optimization&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Route-Optimization&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Route-Optimization&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Route-Optimization&type=date&legend=bottom-right" />
</picture>
</a>
</div>
