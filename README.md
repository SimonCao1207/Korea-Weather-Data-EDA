# Korea Weather Data EDA (in progress)

- Source of data is [here](https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36)

- Information provided includes:
    - Temperature
    - precipitation
    - Wind
    - Atmospheric pressure
    - Humidity
    - Solar radiation
    - Sunlight
    - Snow
    - Cloud
    ...

## Issue with font when displaying Korean character.
- First, you need to install the font Malgun Gothic by installing file `malgun.ttf` to display Korean letter in matplotlib.
- Run the following command to empty cache of matplotlib

    ```shell
    rm ~/.cache/matplotlib -rf
    ``` 
    
- Restart the kernel of the notebook if you have already been active.

## TODO
- [x] Plot graphs tools like matplotlib, seaborn...
- [x] Clean the data with pandas
- [x] Explore some insights about weather in Korea, especially in summer. 
- [ ] Upload the dataset on kaggle