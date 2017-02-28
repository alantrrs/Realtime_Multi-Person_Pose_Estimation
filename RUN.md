# RUN

## Build image
```
docker build -t pose-estimation . 
```

## Download data
```
cd testing
./get_models.sh
```

## Run docker container + program
```
./run_container.sh
python run.py
```
The program should generate a file called ``limbs.png``
