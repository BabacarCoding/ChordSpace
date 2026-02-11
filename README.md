# CHORDSPACE

The goal of this project is to create a program that can detect chord progressions in gospel/church music, with and without instruments.
The project will run with a machine learning model, a database of popular chord progressions, etc.

## Table of Contents
- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)

## Background
**Overview** <br>
Chord detection is a personal project aimed at exploring how musical harmony can be modeled using mathematical representations and principles from Linear Algebra, optimization, and machine learning. Inspired by the <i>Intelligence</i> unit of CS 2740 at GaTech, this project explores how musical information - keys, chords, and progressions - can be inferred from raw audio input through mathematical models.

**Motivation** <br>
Many existing tools are capable of detecting individual chords from audio recordings. However, they often exhibit key limitations:
- Limited progression awareness
    - Most tools can detect chords played however struggle to model the harmonic relationships that define chord progessions within a key.
- Reduced robustness on vocal audio
    - Systems trained primarily on instrument data struggle with vocal recordings.<br>

This project aims to address these gaps by modeling harmony as a mathematical object instead of a collection of isolated predictions.

**Problem Statement** <br>
Given an audio recording of a song (instrument or vocal), the goal is to:
- Infer the musical key of a song
- Identify the sequence of chords present
- Represent the chord progression numerically

**Status** <br>
The project is in its early exploratory stages. Initial efforts are on defining representations and mathematical models on small data sets before moving to larger audios and learning-based methods.

## Installation

## Usage

## Contribution
**Babacar Drame** <br>
Project creator and primary contributor.

The project was initiated, designed, and developed by Babacar Drame. All core ideas, modeling decisions, and implementation efforts are a result of independent experimentation and study.

The conceptual direction of the project is inspired by the <i>Intelligence</i> unit of CS 2740 at Georgia Tech, taught by Professor Gerandy Brito, whose course discussion on intelligence and representations strongly influenced this work.

All contributions are limited to the author.

