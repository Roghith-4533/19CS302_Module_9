# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE:
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1.Start.

2.Define a variables.

3.Write a functions to traverse the linked list and display it in the following format.

4.Read the value using scanf.

5.Ask the user to make an input.

6.Print out the answer.

7.End

## Program:
```
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:
![WhatsApp Image 2025-05-21 at 09 58 22_01b0d927](https://github.com/user-attachments/assets/8a3400d1-fa2f-4651-98d6-d1e287f9ce56)

## Result:
Thus the program was executed and the output was verified successfully.
