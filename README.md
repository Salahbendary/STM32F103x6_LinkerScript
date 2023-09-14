# STM32F103x6 Linker Script

<img src="https://www.disk91.com/wp-content/uploads/2018/09/12180191.png" alt="STM32 Logo" width="100" height="100">

This repository contains the Linker Script for the STM32F103x6 microcontroller.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)


## Overview
A linker script file for the STM32F103x6 microcontroller contains implementation of ROM (Flash) and RAM (Memory) with addresses as mentioned in a datasheet.

## Getting Started

You need to STM32F103x6 controller and ST-Link to debug, also IDE for me STM32Cube IDE. 

# Clone the repository
git clone https://github.com/Salahbendary/STM32F103x6_LinkerScript.git

## File Structure

- LinkerScript.ld: Linker script file contatining the implementation of ROM (Flash) and RAM (Memory) with addresses as a data sheet of STM32f103x6
- file1 & file2 to link them together and store the variables depends on each type @ memory segments and ROM
- application.c: An example file to make sure that linker script work properly
