class IfElseDemo {
    public static void main(String[] args) {

        int testscore = 76;
        char grade;

        if (testscore >= 90) {
            grade = 'A';
            //If testscore is bigger than or equal to 90, grade = A
        } else if (testscore >= 80) {
            grade = 'B';
            //If testscore is bigger than or equal to 80, grade = B
        } else if (testscore >= 70) {
            grade = 'C';
            //If testscore is bigger than or equal to 70, grade = C
        } else if (testscore >= 60) {
            grade = 'D';
            //If testscore is bigger than or equal to 60, grade = D
        } else {
            grade = 'F';
            //Otherwise, grade = F
        }
        System.out.println("Grade = " + grade);
        //Print the grade
    }
}

2. 