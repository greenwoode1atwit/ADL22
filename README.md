# ConvNet

## 1. Introduction:
- What is your MSE/MAE with linreg vs tuned network?

Linreg/TunedNet is 27.86/21.52 after adding a layer and giving it more than 1 braincell
- What happens to your train and test results if you add 5 hidden layers with 128 neurons each?
it go brr

## 2. Padding:
- What is a response layer? (Give a brief, 1-sentence description)
- Given the filter shape of (26, 26, 32), what does each number represent?
- Given 6x6 input and filter of (3,3): what is the response shape that we get? 
- Given (33, 33, 1) input and filter of (2,2): what is the response shape that we get?
- What is the difference between ‘valid’ and ‘same’ padding? Given 6x6 input and filter of (3,3), what are the response shapes for both options?

## 3. Stride and Pooling:
- What is max pooling? (Give a brief, 1-sentence description)
- If I apply pooling of 2 (2,2 window with a stride of 2) to a (6,6) array, what is the resulting size?

## 4. Layers:
- Define I, O, F, S, P as used in this lecture (Give a brief, 1-sentence description)
- What is my output size if Input = (100, 100), kernel size=(2, 2), the stride of 1, and no pooling?
- How many weights do I have if I have 24 such filters stacked (conv2_24)?
- Solve for the padding (P), in terms of I, F, and S, if we want the input and output size to remain the same.

## 5. Practical Patterns
- What can we use the ImageDataGenerator for? What can it help us fight? (Give a brief, 1-sentence description)
- What is a better idea: To use one larger kernel (8,8) or multiple stacked smaller ones, 4x(2,2)? Why? Show the number of weights for each option.
