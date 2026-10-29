\# Week 1



\## Day 3

\*\*Done:\*\* GitHub profile README, 3Blue1Brown ep 1-2, Valid Parentheses



\*\*What a neuron does:\*\* \[a neuron can have a memory like a number(0,1) in the sence of a computer]

\*\*Weights and biases:\*\* \[It is the number held by the neuron that decide the activation of a neuron]

\*\*What the loss is:\*\* \[loss is somthing that shows how much the prediction is different from the actual value]

\*\*Why gradient descent moves downhill:\*\* \[Because we want to minimize the cost function which is possible when we reach the minimum point in the cost function]



\*\*DSA:\*\* Valid Parentheses. Used a stack because the last opened bracket

must be closed first. Time complexity: O(n).



\*\*Stuck on / want to revisit:\*\* \[anything that confused you]







\## Day 4

\*\*Done:\*\* 3Blue1Brown ep 3-4, Best Time to Buy and Sell Stock, Maximum Subarray



\*\*Loss:\*\* \[how wrong the prediction is ]

\*\*Gradient descent:\*\* \[how wring the value]

\*\*Backpropagation:\*\* \[checking all the value that effect the final activation ]

\*\*Why "back":\*\* \[cuz it tracks every neuron that caused chande in the neuron after it]

\*\*Still unsure about:\*\* \[your words]



\*\*DSA:\*\* Best Time to Buy and Sell Stock: one pass, track the minimum

price so far. O(n). Maximum Subarray: Kadane's, extend or restart. O(n).







\## Day 5

\*\*Done:\*\* PyTorch environment, tensors, Group Anagrams



\*\*Setup:\*\* env `dl` (Python 3.11), installed PyTorch using pytorch.org selector

\*\*Tensor things I learned:\*\* \[shape, dtype, indexing, reshape, @ vs \*]

\*\*Error I hit and how I fixed it:\*\* \[your note]

\*\*DSA:\*\* Group Anagrams



Day 6 :
Dataset:{.We loaded the data sets from the Tensor name:[FashionMNIST] 
         . it is a dataset that consist of the images of the humanwares with the there names labeld
.images of pixelsize:[28x28] 
}

Dataloaders={.dataloaders is as the name suggests it loads the data to the modal,
.it will load the data in batchs_size:[amount of data groupd together per step]
.}

