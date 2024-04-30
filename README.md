Class 1 of learning react

what we learnt?

1. Virtual DOM : Virtual DOM is basically the latest copy of real DOM

2. React compares the virtual DOM with the real DOM and updates only changes, not full web page, thus reducing the load on server.

3. There are two methods with react to do so..
    1. Updation : Updates only the changes
        (used when there are less number of changes)
    2. Re-rendering : It as the name says updates the full website or component
        (used when there are more number of changes because of which updating the full component or web page will require less memory as compared to inidvidually updating of each component)


4. These both above mentioned methods are collectively known as Reconciliation.

5. Sending data from one file to another in React

    There are two ways to send data : 
        1. export default x;                         (this can be done only once in a file)
            (where x holds the data being a variable) and is imported as :
                import xyz from "filename containing 'x'"
                (here xyz can be any variable name under which we want to store the value of x)

        2. export const x;       
                                        (this can be done as many times as we want for each variable in a file)

            (where x holds the data being a variable) and is imported as :
                import {x} from "filename containing 'x'"     

                (here the variable name should be same and should be under curly braces so as the file importing can know that which varibale is to imported from the exporting file);

6. React uses Next.js to make frameworks. to use them we can undertake it by using two methods:

*-    1. Parcel      2. Vite (We'll be using Vite)-*



**********-----------------CODE----------------************

1. to get boilerplate use following command in your cmd:
    npm create vite@latest

2. now provide the reqd info

3. and check opening the folder with vs code by using the following command in terminal:
    npm run dev