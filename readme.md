<div align="center">

<a href="https://github.com/Nikhil-Jangid">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Nikhilesh+Jangid+%F0%9F%91%8B;Robotics+%26+Automation+Engineer+in+the+making;ROS+2+%C2%B7+C%2B%2B+%C2%B7+Python+%C2%B7+Embedded+Systems;Currently+building+an+autonomous+mobile+robot+%F0%9F%A4%96" alt="Typing intro" />
</a>

<p>
  <a href="https://www.linkedin.com/in/nikhilj962"><img src="https://img.shields.io/badge/LinkedIn-nikhilj962-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nikhiljangid962@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Surat-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Open_to-Internships_Jan_2027-2EA043?style=for-the-badge&logo=rocket&logoColor=white" alt="Open to internships" />
</p>

</div>

---

### `$ ros2 node info /nikhilesh_jangid`

```yaml
/nikhilesh_jangid:
  education:   B.E. Robotics & Automation · GEC Rajkot · final year
  subscribers: [ros2_jazzy, gazebo, ros2_control, esp32, raspberry_pi]
  publishers:
    /smart_factory_amr:  in_progress   # M0–M3 done, M4 next
    /home_server:        running       # Docker + Tailscale
  services:
    /internship/request: open          # 3–6 months, Jan 2027
  interests:   [drones, medical_robotics, simulation, automation]
  workflow:    requirements -> decisions -> tests -> CI
```

---

### 🛠️ Featured builds

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 [smart-factory-amr](https://github.com/Nikhil-Jangid/smart-factory-amr)
Autonomous mobile robot for factory material handling, built **simulation-first**.

![ROS 2](https://img.shields.io/badge/ROS_2-Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-Harmonic-F58113?style=flat-square)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

- Diff-drive URDF/Xacro model with calculated inertia
- `ros2_control` + command-timeout safety guard
- LiDAR · IMU · encoders, custom C++ Gazebo plugin
- Found a Gazebo shutdown deadlock → [gz-sim #4173](https://github.com/gazebosim/gz-sim/issues/4173)

</td>
<td width="50%" valign="top">

#### 🖥️ [home-server-dashboard](https://github.com/Nikhil-Jangid/home-server-dashboard)
Dashboard for my self-hosted home server, reached only over a private network.

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)

- Live system stats via Glances
- Service error logs from journald
- Web terminal, 0 exposed ports

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏟️ [campus-sports-integrity-system](https://github.com/Nikhil-Jangid/campus-sports-integrity-system)
Identity-bound platform for college sports week.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

- JWT auth + automated tournament scheduling
- Real-time scoring over WebSockets
- QR check-in with rotating 30 s anti-fraud tokens · 40 unit tests

</td>
<td width="50%" valign="top">

#### 💬 WhatsApp ops platform <sub>🔒 client work</sub>
Legal-firm operations run entirely inside WhatsApp.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-self--hosted-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

- Role-based menus for clients, lawyers, staff, admins
- **2,500+** executions in week one
- **<1%** failures · **~0.22 s** average response

</td>
</tr>
</table>

<details>
<summary><b>🔧 More builds: hardware, automation, older projects</b></summary>
<br>

| Project | What it is | Stack |
|---|---|---|
| WhatsApp Factory Monitor | Discrete-event simulation of machines, a 4-AGV fleet and breakdowns, with 7-scenario what-if comparison | n8n · JavaScript · WhatsApp Cloud API |
| Smart Home System | Team lead: ESP32 firmware, custom PCB, app and voice control | ESP32 · C/C++ · ESP RainMaker |
| Line-Following Robot | Inter-college competition semifinalist, MSU Vadodara | Sensors · motor control |
| RFID Record Player | RFID tags pick the music; stepper-driven platter | Raspberry Pi · Python · Spotify API |
| [python_password_manager](https://github.com/Nikhil-Jangid/python_password_manager) | AES-256 vault with a PBKDF2-derived master key | Python · MySQL |
| [spotify_to_applemusic](https://github.com/Nikhil-Jangid/spotify_to_applemusic) | Moves playlists from Spotify to Apple Music | Python · Spotify & Apple Music APIs |
| [PaidIntern-WebScraping](https://github.com/Nikhil-Jangid/PaidIntern-WebScraping) | Streamlit app that finds doctors by location and specialty | Python · Streamlit · BeautifulSoup |

</details>

---

### 🗺️ AMR roadmap

```text
M0  Dev environment        ██████████  done
M1  Custom robot model     ██████████  done
M2  Basic movement         ██████████  done
M3  Sensors                ██████████  done
M4  Odometry               ░░░░░░░░░░  next
M5  SLAM · M6 Localization · M7 Nav2 · M8 Obstacle avoidance
M9  Factory world · M10 Tasks · M11 Vision · M12 Dashboard
```

---

### ⚙️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,py,js,ts,linux,ubuntu,bash,docker,aws,git,githubactions&perline=12" alt="Languages and tools" />
  <br>
  <img src="https://skillicons.dev/icons?i=raspberrypi,arduino,opencv,nodejs,express,react,flask,postgres,mysql,vscode&perline=10" alt="Hardware and frameworks" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge" alt="Gazebo" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white" alt="Tailscale" />
</p>

---

<div align="center">

**Looking for a 3–6 month robotics internship from January 2027, especially in drone systems or medical robotics.**<br>
<a href="mailto:nikhiljangid962@gmail.com">Let's talk →</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Nikhil-Jangid&style=flat-square&color=22D3EE&label=profile+views" alt="Profile views" />

</div>
