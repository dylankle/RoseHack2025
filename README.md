
# FindHer Restaurant

Our app introduces a fun user experience that helps users pick amongst restaurants generated by our program to shine light on underrepresented groups and local businesses.
This project was made entirely within a 24 hour timeframe for the Rose Hack Hackathon at University of California, Riverside.


## How to Get Started

#### To use you must have an API key from Yelp Fusion. https://business.yelp.com/data/products/fusion/

Create a .env file in the 'rose-hack' directory then add the following parameter:

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `YELP_API_KEY` | `string` | **Required**. Your API key |

Next, from the root directory, open into 'rose-hack' directory, install the required dependencies, then run the local server.
```
cd rose-hack
npm install
npm run dev
```

Lastly, open a new terminal and start the backend server after installing the libraries.
```
cd rose-hack
pip install -r requirements.txt
python main.py
```
On mac:
```
cd rose-hack
pip install -r requirements.txt
python3 main.py
```
## How we built it


The application is comprised of a React frontend connected to a fully python backend via Flask API. We also leveraged from Yelp Fusion API to get valuable data and information about restaurants in user areas that are owned by women and other underrepresented groups.
## Inspiration

All of our friends including ourselves can never decide on what to eat for dinner. On a more serious. note, we found that profit margins between women and male businesses have a huge gap. To raise awareness for marginalized groups, we wanted to make an app to promote women-owned restaurants.
## Authors

- [@aacayanan](https://github.com/aacayanan)
- [@dylankle](https://github.com/dylankle)
