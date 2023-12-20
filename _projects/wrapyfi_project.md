---
layout: page
title: Wrapyfi
description: Wrapyfi is a middleware communication wrapper for transmitting data across nodes, without altering the operation pipeline of your Python scripts. Wrapyfi introduces a number of helper functions to make middleware integration possible without the need to learn an entire framework, just to parallelize your processes on multiple machines. Wrapyfi supports YARP, ROS, ROS 2, and ZeroMQ.
img: https://raw.githubusercontent.com/fabawi/wrapyfi/main/assets/wrapyfi.png
importance: 1
category: work
related_publications: abawi2024wrapyfi
---

Message oriented and robotics middleware play an important role in facilitating robot control, abstracting complex functionality, and unifying communication patterns between sensors and devices. However, using multiple middleware frameworks presents a challenge in integrating different robots within a single system. To address this challenge, we present Wrapyfi, a Python wrapper supporting multiple message oriented and robotics middleware, including ZeroMQ, YARP, ROS, and ROS 2. Wrapyfi also provides plugins for exchanging deep learning framework data, without additional encoding or preprocessing steps. Using Wrapyfi eases the development of scripts that run on multiple machines, thereby enabling cross-platform communication and workload distribution. We finally present the three communication schemes that form the cornerstone of Wrapyfi's communication model, along with examples that demonstrate their applicability.
