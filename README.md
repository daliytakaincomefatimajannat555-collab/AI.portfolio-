# AI.portfolio-
ai-portfolio-dashboard/ ├─ public/ │   └─ content/ │       └─ chartData.json ├─ server/ │   └─ server.js ├─ src/ │   ├─ index.html │   ├─ main.js │   ├─ App.js │   ├─ styles.css │   └─ components/ │       ├─ LiveChart.js │       └─ EditableText.js ├─ package.json ├─ vite.config.js └─ README.md
{
  "Skills": {
    "labels": ["React", "Node.js", "AI", "CSS", "Python"],
    "datasets": [{
      "label": "Skill Level",
      "data": [85, 75, 90, 80, 70],
      "backgroundColor": ["#4caf50","#2196f3","#ff9800","#9c27b0","#f44336"]
    }]
  },
  "Projects": {
    "labels": ["Project A", "Project B", "Project C"],
    "datasets": [{
      "label": "Completion %",
      "data": [100, 60, 80],
      "backgroundColor": ["#3f51b5","#e91e63","#00bcd4"]
    }]
  },
  "Analytics": {
    "labels": ["Jan", "Feb", "Mar", "Apr", "May"],
    "datasets": [{
      "label": "Visitors",
      "data": [120, 200, 150, 220, 300],
      "backgroundColor": "#ffc107"
    }]
  }
}
