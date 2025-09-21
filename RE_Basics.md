# **RE Basics**
## **Questions :**

### **1) Describe the fetch-execute cycle.**

#### The process in which the CPU read and executes the instruction is called fetch-execute cycle as the instruction is being read the necessary details from the memory are fetched and then the instruction is executed.
 
### **2) What is a register? How would computation be more difficult without registers?**

####  Registers are high speed memory locations present inside the processors. They are essential for computing as they are the ones which are used as a memory storage while processing the data retrieved from the memory 

### **3) How do you represent numbers larger than 255?**

#### A byte can hold numbers up to 255 ( as 1 byte = 8 bits and the total value if all the bit are 1 would be 255) . When the number gets larger we can combine another bit to store the values larger than 255 . This need some calculation which will be done by the computer up to 4 bytes(1 word in x86 processors).

### **4) How big are the registers on the machines we will be using?**

#### In a x86 architecture based system each register will be 4-byte long which is called the *word* size of a computer .

### **5) How does a computer know how to interpret a given byte or set of bytes of memory?**

#### The computer will just follow the instructions we give blindly. It doesn’t know how to interpret a memory exactly. For a set of bytes we can store different data on different addresses using offsets to let the computer know while interpreting.

### **6) What are the addressing modes and what are they used for?**

#### Addressing modes are the different ways  which are used by the CPU to access the data from the memory. They involve different modes to access and retrieve the data from the memory. Involves different modes like

- #### immediate mode 
- #### register addressing mode 
- #### direct addressing mode
- #### register addressing mode 
- #### indexed addressing mode 
- #### indirect addressing mode
- #### base pointer addressing mode

### **7) Whatdoes the instruction pointer do?**
#### instruction pointer is the pointer which is used by the computer to identify instructions . This points to a memory word which will be loaded as an instruction
