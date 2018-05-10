[![Build Status](https://travis-ci.org/jonghough/Calendar-jx.svg?branch=master)](https://travis-ci.org/jonghough/Calendar-jx)
# Calendar-JX

Single-user local Calendar Schedule App

## Java Calendar Demo

This is a simple demo of a calendar and schedule app, written in Java,
and Spring-Boot, and the front-end using bootstrap and jquery.

## Functionality

The app uses a local SQLite database to store the data, and allows the user
to input schedule appointments for a given date and time, and a note or
reminder for the user to read.

## Usage

`mvn exec:java`

The app listens on port *9999* by default, which is set in the properties file. The SQLite database is by default in the */tmp* directory, for demo usage. For real usage, this should be changed.
