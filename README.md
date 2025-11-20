# AI-Powered Sales Analysis Dashboard  

**Live App:** https://ai-analysis-app-4gkgaiaey8jv7nbuniezjm.streamlit.app/

## Project Overview  
This interactive web application visualizes the AI Usage Analysis in Student Life performed by our team for the DTSC201 final project. Built entirely in Python using **Streamlit**, it transforms our Jupyter notebook analysis into a user-friendly, shareable dashboard that can be accessed by anyone with a browser.

## Features  
- Multi-page navigation (Overview → Outcome & Usage → Prompt by Discipline → Satisfication Rating Analysis → Session Correlation → Student Level Analysis → Task Type Analysis → Insights)  
- Interactive charts and graphs using Matplotlib, Seaborn
- Clean, responsive layout with sidebar navigation  
- Fully deployed and publicly accessible via Streamlit Community Cloud  

# Development Journey  
| Stage                        | Tool Used                     | Purpose                                                                 |
|------------------------------|-------------------------------|-------------------------------------------------------------------------|
| Initial Analysis & Prototyping | **Jupyter Notebook**          | EDA, testing visualizations, finding insights                           |
| Final Interactive App         | **Streamlit + Python**       | Converted notebook → clean multi-page web dashboard                      |
| Remote Editing & Deployment   | **GitHub Codespaces + CLI**   | Seamless editing and instant deployment without local setup             |
| Hosting                       | **Streamlit Community Cloud** | Free, public, always-on link                                            |

## Tech Stack  
- **Streamlit** – for the web interface and deployment  
- **Python** – Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- **GitHub + GitHub Codespaces** – for collaborative development and remote editing  
- **Streamlit Community Cloud** – free hosting and instant deployment  

## What We Learned  
| Challenge                              | Solution & Lesson Learned                                                                 |
|----------------------------------------|--------------------------------------------------------------------------------------------|
| Converting Jupyter notebooks → Streamlit | Rewrote analysis as modular Python scripts; used `st.set_page_config()` and `pages/` folder |
| Deployment kept failing                 | Discovered we needed a `requirements.txt` listing all imported packages                     |
| Sidebar pages not appearing            | Learned pages must be in a folder named exactly `pages/` with files like `1_Overview.py`   |
| Local → GitHub sync issues             | Used GitHub Codespaces + CLI (`git add .`, `commit`, `push`) for seamless remote workflow  |

It took **~3 weeks** to fully migrate, debug, and polish the app — but now it's smooth, fast, and looks professional!
