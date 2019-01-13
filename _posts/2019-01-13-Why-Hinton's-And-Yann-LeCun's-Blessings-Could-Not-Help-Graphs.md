---
layout: post
title: Why Hinton's And Yann LeCun's Blessings Could Not Help Graphs
subtitle: How and Why Deep Learning on graphs is different from Deep Learning on images.
---

Let me be honest, graphs are my favourite datastructure and graph theory is just incredible. I love graphs so much that I regularly visit [Zachary's Karate Club](https://en.wikipedia.org/wiki/Zachary%27s_karate_club).
![Zachary's Karate Club](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Social_Network_Model_of_Relationships_in_the_Karate_Club.png/750px-Social_Network_Model_of_Relationships_in_the_Karate_Club.png)


Deep Learning is good at extracting complex patterns from data. Data modelled as graphs- social networks, e-commerce networks, biology networks, traffic networks... are readily available, but they are the beyond what Yann LeCun's convolution can handle . Applying deep learning to the ubiquitous graph data is non-trivial because of the unique characteristics of graphs.This problem is nontrivial because several challenges exist for applying traditional deep learning architectures to graphs.

1.Irregular domain

Unlike images, audio and text whichhave a clear grid structure, graphs lie in an irregular domain, making it hard to generalize some basic mathematical operations to graphs. For example, it is not straight-forward to define convolution and pooling operation for graph data, which are the fundamental operations in Convolutional Neural Networks (CNNs). This is often referred as the Geometric Deep Learning problem.
![Geometric](https://i.ibb.co/fnJtJWH/Screenshot-86.png)
