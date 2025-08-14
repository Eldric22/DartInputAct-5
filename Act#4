import 'dart:io';

void main() {
  print("=== User Registration ===");

  stdout.write("Enter your Firstname: ");
  String? firstName = stdin.readLineSync();

  stdout.write("Enter your Lastname: ");
  String? lastName = stdin.readLineSync();

  stdout.write("Enter your Email Address: ");
  String? email = stdin.readLineSync();

  if (firstName != null && firstName.trim().isNotEmpty &&
      lastName != null && lastName.trim().isNotEmpty &&
      email != null && email.trim().isNotEmpty) {
    print("\n=== Registration Summary ===");
    print("Name  : $firstName $lastName");
    print("Email : $email");
  } else {
    print("Please provide all required information.");
  }
}