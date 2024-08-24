#include <stdio.h>
#include <string.h>

void EngAndIt() {
    printf("\n ----------------------------------------\n");
    printf("\n ----------------------------------------\n");
    printf("You have chosen School of Engineering and IT \n ");
    printf("== Books available for you: \n\n");
    printf("1. C++ \n");
    printf("2. C \n");
    printf("3. Python \n");
    printf("4. Java \n");
    printf("5. Web Development \n");
    printf("6. C# \n");
}

void management() {
    printf("\n ----------------------------------------\n");
    printf("\n ----------------------------------------\n");
    printf("You have chosen School of Management \n ");
    printf("== Books available for you: \n\n");
    printf("1. Principles of Management \n");
    printf("2. Accountancy \n");
    printf("3. Business Ethics \n");
    printf("4. Macroeconomics \n");
    printf("5. Microeconomics \n");
    printf("6. Business Communication \n");
}

void pharmacy() {
    printf("\n ----------------------------------------\n");
    printf("\n ----------------------------------------\n");
    printf("You have chosen School of Pharmacy\n ");
    printf("== Books available for you: \n\n");
    printf("1. Human Anatomy \n");
    printf("2. Human Cells and Their Functions \n");
    printf("3. Medical Mastery \n");
    printf("4. Pharmaceutical Organic Chemistry \n");
    printf("5. Remedial Biology \n");
    printf("6. Pharmaceutics \n");
}

void law() {
    printf("\n ----------------------------------------\n");
    printf("\n ----------------------------------------\n");
    printf("You have chosen School of Law\n ");
    printf("== Books available for you: \n\n");
    printf("1. Indian Constitution \n");
    printf("2. IPC and BNS \n");
    printf("3. Laws Related to Business and Politics \n");
    printf("4. Corporate Law \n");
    printf("5. Contract Law \n");
    printf("6. Human Rights & International Law \n");
}

int main() {
    int branch;
    char book[50];
    char name[50];
    int enroll;

    printf("-------------------------------------------\n");
    printf("*****  LIBRARY MANAGEMENT SYSTEM  *****");
    printf("\n----------------------------------------\n");

    printf("Select your Branch: \n");

    printf("1. School of Engineering and IT\n");
    printf("2. School of Management\n");
    printf("3. School of Pharmacy\n");
    printf("4. School of Law\n");

    scanf("%d", &branch);
    getchar(); // to consume the newline character left by scanf

    switch (branch) {
        case 1: EngAndIt();
                break;
        case 2: management();
                break;
        case 3: pharmacy();
                break;
        case 4: law();
                break;
        default: printf("Invalid choice!\n");
                 return 1;
    }
    printf("\n ----------------------------------------\n");

    printf("Enter the name of the book you want to borrow: \n");
    fgets(book, sizeof(book), stdin);
    book[strcspn(book, "\n")] = '\0'; // remove the newline character

    printf("You have chosen %s\n", book);
    printf("\n");

    printf("Enter your name: \n");
    fgets(name, sizeof(name), stdin);
    name[strcspn(name, "\n")] = '\0'; // remove the newline character

    printf("Enter your Enrollment number: \n");
    scanf("%d", &enroll);

    printf("\n");
    printf("Your record has been recorded.\n\n");
    printf("As per the policy, you have to return the book within 21 days of borrowing.\n");
    printf("Your schedule time will be allotted to you within 2 hours. Kindly reach the library on time with your schedule time proof.\n");
    printf("\nTHANK YOU!\n");

    return 0;
}
