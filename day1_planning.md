# Day 1 – Project Planning

## Project Title
MacBook Pro M2 Cybersecurity Homelab: Energy Company Simulation

## Project Overview
This project simulates the cybersecurity environment of an energy company using a MacBook Pro M2-based homelab. The lab will include an Ubuntu Server representing a company system, a Kali Linux machine representing external testing activity, and monitoring tools such as Wireshark and Nmap. The goal of the project is to analyze network traffic, identify exposed services, simulate suspicious activity, and practice incident response in a controlled environment.

## Company Scenario
Company Name: GridSecure Energy

Industry: Energy / Utilities

The company operates infrastructure systems and internal servers that must be protected from cyber threats.

Possible threats include:
- network scanning
- unauthorized login attempts
- exposed services
- credential attacks

## Lab Systems
Ubuntu Server
Role: company server

Kali Linux
Role: external testing machine

MacBook Pro M2
Role: host system running the lab

## Lab Architecture
MacBook Pro M2 (Host)
        │
       UTM
      /   \
Ubuntu   Kali
Server   Linux

## Security Goals
- observe network traffic
- identify open ports
- simulate suspicious activity
- analyze logs
- practice incident response

## Learning Objectives
- understand virtualization
- learn Linux server basics
- analyze network traffic
- identify exposed services
- document security findings