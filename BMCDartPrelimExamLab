import 'dart:io';

void main() {
  print(" Enter your name: "); // i add this name for the student
  String? name = stdin.readLineSync();

  try {
    print("Enter Assignment score:"); // printing the assignment score
    double assignment = double.parse(stdin.readLineSync()!);

    print("Enter Midterm score:"); // printing the midterm score
    double midterm = double.parse(stdin.readLineSync()!);

    print("Enter Final Exam score:"); // printing the midterm score
    double finalExam = double.parse(stdin.readLineSync()!);

    // weight of each component in the final calculation
    double passingGrade = 60.0;
    double assignmentWeight = 0.2;
    double midtermWeight = 0.3;
    double finalExamWeight = 0.5;

    double finalGrade =
        (assignment * assignmentWeight) +
        (midterm * midtermWeight) +
        (finalExam *
            finalExamWeight); // this is the calculation of final grade by applying assignment midterm and finalexam

    print("\n Hi ${name}, here is your grade report:");
    print("Assignment Score: ${assignment.toStringAsFixed(1)}");
    print("midterm Score: ${midterm.toStringAsFixed(1)}");
    print("finalExam Score: ${finalExam.toStringAsFixed(1)}");
    print("Final Grade: ${finalGrade.toStringAsFixed(1)}");

    if (finalGrade >= passingGrade) {
      // using this if else to show their grade if pass or failed
      print("Passed!");
    } else {
      print("sorry you Failed.");
    }
  } catch (e) {
    print(
      "Error: Please enter valid numeric scores only.",
    ); // to return and enter another valid number
  }
}
