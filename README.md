# AI Resume Analyzer & Interview Preparation System

## 📌 Project Overview

The AI Resume Analyzer & Interview Preparation System is a Prompt Engineering project designed to analyze a candidate's resume against a Software Developer job description.

The system identifies relevant skills, finds potential skill gaps, generates personalized interview questions, and evaluates the generated questions before producing a final interview preparation report.

## 🎯 Objective

To design a structured AI workflow that analyzes candidate information, compares it with job requirements, identifies skill gaps, and generates relevant interview questions using effective Prompt Engineering techniques.

## ❗ Problem Statement

HR recruiters may spend significant time manually analyzing resumes according to specific job requirements, identifying relevant skills and preparing suitable interview questions.

This project uses Prompt Engineering to create a structured and repeatable workflow for these tasks.

## ⚙️ Workflow

Resume + Job Description  
↓  
Information Extraction  
↓  
Skill Gap Analysis  
↓  
Interview Question Generation  
↓  
Question Evaluation  
↓  
Final Interview Report

## 🧠 Prompt Engineering Techniques Used

- Role Prompting
- Contextual Prompting
- Prompt Decomposition
- Prompt Chaining
- Structured Outputs
- Grounding
- Hallucination Control
- Prompt Evaluation
- Prompt Refinement
- Prompt Optimization

## ✨ Key Features

- Extracts candidate information from resumes
- Extracts requirements from job descriptions
- Compares candidate skills with job requirements
- Identifies potential skill gaps
- Generates personalized interview questions
- Includes technical, project-based and problem-solving questions
- Evaluates generated questions
- Produces a structured final interview report

## 📊 Final Output

The system generates a structured report containing:

- Candidate Profile
- Job Requirements
- Matching Skills
- Skills Not Mentioned in Resume
- Skill-Gap Based Questions
- Technical Questions
- Project-Based Questions
- Problem-Solving Questions
- Question Quality Evaluation
- Final Interview Preparation Summary

## 🔍 Important Design Principle

The system does not assume that a candidate lacks a skill simply because the skill is not mentioned in the resume.

For example:

> React.js — Not mentioned in resume

instead of:

> Candidate does not know React.js.

This helps reduce unsupported assumptions and improves the reliability of the analysis.

## 📁 Project Structure

```text
AI-Resume-Analyzer-Prompt-Engineering/
│
├── README.md
├── prompts/
├── sample_data/
├── outputs/
├── evaluation/
└── documentation/
