# **Traffic light classifer**

### Objective
Use a nerual network to predict the state of a traffic lights, e.g. "red", "yellow", "green", "off"


#### Current accuracy:

94.2% at Bosch dataset, Udacity simular and udacity car dataset.




#### The state definition of the traffic lights are as follow:

| Traffic light state 	| red 	| yellow 	| green 	| off 	|
|:-------------------:	|:---:	|:------:	|:-----:	|:---:	|
| Index 	| 1 	| 2 	| 3 	| 4 	|



#### How to run the demo

```sh

python main.py

```

#### How to run with your own image

![alt text][green]

```sh
    file_path = './data/green.jpg'
    predicted_state = test_an_image(file_path, model=load_model('model.h5'))
```

```sh
Output: green
```

[green]: ./data/green.jpg
