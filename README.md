# Plant-Disease-Detection-Website
Web-based Plant Disease classifier written in Pytorch.


## Project Structure

├── app
│   ├── ai
│   ├── main.py
│   └── web
│       ├── backend
│       │   ├── error
│       │   ├── home
│       │   └── login
│       └── frontend
│           ├── css
│           ├── html
│           └── javascript
├── LICENSE
├── README.md
└── test

### app/

This is the directory related to the backend and frontend

### app/ai/

Models, train, test, data processing and similar.

## app/web/frontend/

HTML, Javascript and CSS files organized.

## app/web/backend/

Backend files.

## Dataset citation

In accordance with the [dataset provider](https://github.com/spMohanty/PlantVillage-Dataset/tree/master) their research is cited below:

```latex
@article{Mohanty_Hughes_Salathé_2016,
    title   = {Using deep learning for image-based plant disease detection},
    volume  = {7},
    DOI     = {10.3389/fpls.2016.01419},
    journal = {Frontiers in Plant Science},
    author  = {Mohanty, Sharada P. and Hughes, David P. and Salathé, Marcel},
    year    = {2016},
    month   = {Sep}
} 
```
