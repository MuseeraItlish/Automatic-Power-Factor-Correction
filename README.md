# Automatic-Power-Factor-Correction

## Overview

This project implements an Automatic Power Factor Correction (APFC) system using an Arduino ATmega328 to improve power factor in AC electrical systems with inductive loads such as submersible pumps and bulbs. The system continuously measures electrical parameters and automatically switches capacitor banks to compensate for reactive power.

The goal is to reduce energy losses, improve efficiency, and lower electricity costs, especially in rural and small industrial applications.

## Key Features

-Real-time measurement of voltage, current, power, and power factor

-Automatic capacitor switching using relay modules

-Power factor improvement from 0.66 to 0.92

-Live system monitoring on a 16×4 LCD

-Low-cost and scalable design

## Hardware Used

-Arduino Uno (ATmega328)

-PZEM-004T Power Measurement Module

-Relay Module

-Capacitor Bank

-16×4 LCD Display

-Submersible Pump / Bulb (Load)

-AC Power Supply

## Working Principle

Inductive loads cause current to lag voltage, reducing power factor and increasing losses.
The PZEM-004T module measures real-time electrical parameters and sends them to the Arduino.
When the power factor falls below a set threshold, the Arduino activates relays to connect appropriate capacitors in parallel with the load. These capacitors supply leading reactive power, reducing the phase angle and improving the power factor.

All system parameters are displayed in real time on an LCD.

## Applications

-Rural electrical systems

-Agricultural water pumping systems

-Small industrial setups

-Energy efficiency improvement projects

-Power quality enhancement

## Advantages

-Reduces reactive power losses

-Improves system efficiency

-Lowers electricity bills

-Fully automatic operation

-Simple and economical design

## Limitations & Future Scope

### Limitations

  -Correction limited by capacitor bank size

  -Reactive (not predictive) control

  -No remote monitoring

### Future Improvements

  -IoT-based remote monitoring
  
  -Wireless data logging (Wi-Fi / GSM)
  
  -Smart predictive control algorithms
