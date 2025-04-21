---
layout: page
title: Document OCR Processor
date: 2024-04-01
description: Getting LLMs to extract text from documents while preserving formatting
img: # Optional: Path to a representative image
importance: 1
category: personal
github: nijinjose/document-ocr-processor
---

## The Problem

If you've ever tried to extract text from images of documents, you know the pain. Traditional OCR tends to mess up formatting, tables get destroyed, and columns become a jumbled mess. I needed something that could extract text while keeping the content structured like the original.

## My Solution

I built a Python tool that leverages Google's Gemini 2.0 Flash LLM to handle document image OCR tasks. Unlike traditional OCR, Gemini can actually "see" the document structure and format the extracted text accordingly.

What makes this tool particularly useful is its batch processing capabilities - you can throw a folder of document images at it, and it will process them all while tracking progress. It's also reasonably smart about error handling, so if one image fails, it won't crash the entire batch job.

## How It Works

1. Images are processed one by one or in batches
2. Each image is sent to Google's Gemini 2.0 Flash API
3. The LLM "sees" the document and extracts text with formatting
4. Results can be saved as individual files or consolidated into one document
5. Progress is tracked throughout for longer batch jobs

## The Tech

- Python for application and CLI implementation
- Google Gemini API (Flash 2.0 LLM) for intelligent document "understanding"
- Command-line interface for easy batch processing
- Progress tracking and error handling for reliability

I found Gemini particularly good at preserving tables, columns, and document hierarchies - things that traditional OCR tools struggle with.
