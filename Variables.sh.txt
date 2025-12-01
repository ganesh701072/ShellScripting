#!/bin/bash

#variables

name="Ganesh"

#input name

read -p "Enter Your Company Name:" company
read -p "Year of Joining:" YOJ
CY=2025
EXP=$(($CY-$YOJ))
echo "Employee Name: $name"

echo "Company Name: $company"

echo "Years of Experience: $EXP"
