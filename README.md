<h2>Weather App 🌦️<br></h2><br>
Course Work (for Gomel State University Spring 2025)<br><br>
A beautiful and functional mobile weather application developed using Flutter / Dart. The app features a dynamic user interface that changes colors based on the time of day and implements a custom sorting algorithm for forecast data.

<br>
✨ Core Features
• Dynamic Themes: The interface automatically switches gradients and color schemes based on the time of day (Morning, Afternoon, Evening, Night).
• Hourly Forecast: A clean, horizontal scrollable view tracking hourly temperature changes.
• Astronomical Data: Specialized panel displaying accurate sunrise and sunset times parsed directly from the weather API.
• City Selection: An interactive dropdown menu containing major cities (Minsk, Gomel, Brest, Vitebsk, Grodno, Mogilev).
• Smart Sorting: Custom implementation of the Quick Sort algorithm to organize forecast days by temperature (from coldest to warmest and vice versa).

📁 Project Structure (lib/)
<br>
lib/
├── main.dart<br>                  — Entry point, initializes MyApp and WeatherHome
├── sunrise_sunset.dart<br>        — Custom widget for displaying sunrise and sunset times
├── algorithm/<br>
│   └── quickSort.dart <br>        — Custom sorting algorithm for forecast days
└── body/<br>
    ├── service.dart  <br>         — WeatherService (handles HTTP API requests)
    ├── tools.dart   <br>          — HourlyCard widget for hourly weather blocks
    └── glass_container.dart<br>   — GlassContainer widget creating a frosted glass effect
⚙️ Quick Sort Algorithm<br>
The application uses an independent implementation of the Quick Sort algorithm with a time complexity of O(n log n) to sort forecast days based on their maximum temperature (maxtemp_c)
🛠️ Tech Stack<br>
• Language: Dart<br>
• Framework: Flutter<br>
• Architecture: Component-based separation (Services, UI Widgets, and Logic)<br>
• API Integration: REST API (Parsing complex JSON responses, including historical and astro data objects)<br>
<img width="1386" height="779" alt="sunset" src="https://github.com/user-attachments/assets/d0f7e5aa-477e-4cfc-9f20-6c3a35ac78a7" /><br>
<img width="736" height="720" alt="region" src="https://github.com/user-attachments/assets/34419c93-f0d8-4d12-8cd0-be7b20292ef9" /><br>
<img width="1381" height="720" alt="test1" src="https://github.com/user-attachments/assets/68e75400-51cb-47b6-a5f8-e65c2ec634fe" /><br>
<img width="849" height="603" alt="arhitecture" src="https://github.com/user-attachments/assets/f63a5816-1b30-4c48-b867-5fc39eb52c1d" /><br>
<img width="1370" height="779" alt="sort" src="https://github.com/user-attachments/assets/978d6402-2694-47db-90c7-33644c225e4a" /><br>
