#!/bin/bash

echo "Welcome to signup page"

echo "Please enter your name"

read name

echo "****************"

echo "Please enter your email"

read email

echo "*****************"

echo "Please enter the password"

read -s password # -s hides the input

echo "Please confirm your password"

read -s confirm # -s hides the input

echo "******************"

if [ "$password" == "$confirm" ]; then

echo "Your signup is successful!"

echo "Name: $name"

echo "Email: $email"

else

echo "Passwords do not match! Please try again."

fi





