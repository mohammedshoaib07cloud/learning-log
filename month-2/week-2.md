Day-8 
for the first time i have trained a deep learning model which will pridict the cloth 
.it takes the image of [28x28]pixel=784 and pridits the cloth type in 10 different classes: 
.it have 4 layers with different operations
     -> nn.Flatten() will convert the pixcel in one line 
     -> nn.Linear() will convert 784 nodes to 128
     -> nn.ReLU() sets negative to zero
     -> nn.Linear()will turn 138 featurs into 10 
the highest value from the 10 will be the pridiction of the class
zero_grad=to let the model learn cuz it will get added up 
backword()=means backtraacking
eval()=it will pridict the 10,000 it has never trained on and count the correct gusses 
no_grad()=