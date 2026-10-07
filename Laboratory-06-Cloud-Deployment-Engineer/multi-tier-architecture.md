# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture separates an application into two main parts: the Web/Application Tier and the Database Tier. The application communicates with the database to store and retrieve persistent information.

## The Web/Application Tier

The Web/Application Tier is responsible for serving the user interface and handling HTTP requests from users. In this mission, the Nextcloud container acts as the application tier and provides the cloud storage web interface.

## The Database Tier

The Database Tier stores persistent application data such as user accounts, configuration information, and other database records. In this mission, MariaDB is used as the database server.

## Why Separate Them?

Separating the web server and database into different containers makes the system easier to manage, maintain, and scale. Each container has a specific responsibility, so problems or changes in one tier can be handled without modifying the other tier.
