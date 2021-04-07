# Face Mask Detection using Yolov3 and Yolov4

## Steps for training your own custom face mask detector using yolov3 and yolov4 in google colab

### First add the all cfg files to google colab(They are in the respective directory)
```
For yolov3 add:-
    class.names
    yolov3-mask-setup.data
    yolov3-mask-test.cfg
    yolov3-mask-train.cfg
```
```
For yolov4 add:-
    class.names
    yolov4-mask-setup.data
    yolov4-mask-test.cfg
    yolov4-mask-train.cfg

```

### Then mount your drive so that you will have backup(Run the first code block)

### Run everything now!!

#### Additional tips:

To not get kicked out of google's VM:
Add this code block:
right click -> Inspect element -> Console

```javascript
function ClickConnect(){
console.log("Working"); 
document
  .querySelector('#top-toolbar > colab-connect-button')
  .shadowRoot.querySelector('#connect')
  .click() 
}
setInterval(ClickConnect,60000)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.




