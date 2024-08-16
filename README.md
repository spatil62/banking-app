Banking Application

Overview

The Banking Application is a Spring Boot-based project designed to manage bank accounts through a RESTful API. It allows users to perform common banking operations such as creating accounts, depositing and withdrawing funds, retrieving account details, and deleting accounts.

Features

Account Management: Create, retrieve, update, and delete bank accounts.
Deposit & Withdrawal: Add or remove funds from accounts.
Account Retrieval: Fetch details of specific accounts or list all accounts.
Key Components

AccountController: Handles incoming HTTP requests and maps them to the corresponding service methods.
AccountDto: Data Transfer Object that represents account data.
Account: JPA entity that maps to the database table.
AccountMapper: Converts between Account entities and AccountDto objects.
AccountRepository: Interfaces with the database to perform CRUD operations.
Technologies Used

Spring Boot: Framework for building the RESTful API.
JPA (Java Persistence API): For database interaction.
MySQL: Relational database for storing account information.
Usage

The application provides several endpoints for managing bank accounts:
and covers all CRUD operations 

