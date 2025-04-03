---
layout: page
title: Data Engineering Learning Hub
---

# Data Engineering Learning Hub

Welcome to my Data Engineering learning hub, where I document my journey in building data pipelines, working with data warehousing, and mastering essential data engineering tools. This site serves as a resource for aspiring data engineers to learn and grow.

![Data Engineering Banner](/assets/images/data-engineering-banner.png)

## Learning Tracks

<div class="learning-tracks bl">
  <div class="track">
    <h3>🔄 Data Pipelines</h3>
    <p>Learn how to design and implement robust data pipelines for seamless data flow.</p>
    <a href="/data-engineering/fundamentals/data-pipelines" class="button">Explore Track</a>
  </div>
  
  <div class="track">
    <h3>💾 Data Warehousing</h3>
    <p>Understand how to store and organize data in scalable and efficient data warehouses.</p>
    <a href="/data-engineering/fundamentals/data-warehousing" class="button">Explore Track</a>
  </div>
  
  <div class="track">
    <h3>🔄 ETL Processes</h3>
    <p>Master the Extract, Transform, Load (ETL) processes for efficient data integration.</p>
    <a href="/data-engineering/fundamentals/etl-processes" class="button">Explore Track</a>
  </div>
</div>

## Featured Projects

Explore my hands-on data engineering projects, where I apply the tools and techniques I’ve learned to real-world scenarios.

- **[Building a Real-Time Data Pipeline with Kafka](projects/real-time-pipeline.md)** - A comprehensive project on building a real-time data pipeline using Kafka.
- **[Data Warehouse Setup with Snowflake](projects/data-warehouse-snowflake.md)** - Setting up and optimizing a Snowflake data warehouse.

## Featured Tools

<div class="tools bl">
  <div class="tool">
    <h4>Apache Airflow</h4>
    <p>Orchestrate complex workflows and automate data pipelines with Apache Airflow.</p>
    <a href="/data-engineering/tools/airflows" class="button">Learn More</a>
  </div>

  <div class="tool">
    <h4>Apache Spark</h4>
    <p>Process large datasets at scale with Apache Spark for distributed data processing.</p>
    <a href="/data-engineering/tools/apache-spark" class="button">Learn More</a>
  </div>

  <div class="tool">
    <h4>Kafka</h4>
    <p>Build real-time data streaming applications with Apache Kafka.</p>
    <a href="/data-engineering/tools/kafka" class="button">Learn More</a>
  </div>

  <div class="tool">
    <h4>Snowflake</h4>
    <p>Implement scalable and efficient data warehouses using Snowflake.</p>
    <a href="/data-engineering/tools/snowflake" class="button">Learn More</a>
  </div>
</div>

## Latest Notes

- **[Building ETL Pipelines with Python](/data-engineering/fundamentals/etl-processes)** - Learn the practical aspects of building ETL pipelines using Python.
- **[Data Warehouse Design Best Practices](/data-engineering/fundamentals/data-warehousing)** - Effective design and optimization of data warehouses.

## Get in Touch

Have questions or suggestions? Feel free to:
- Open an issue on [GitHub](https://github.com/duan-n2d/Learning-journey-of-NDoubleD)
- Connect with me on [LinkedIn](https://linkedin.com/in/duannguyen2606)

---

<style>
  /* Global styles */
  body {
    font-family: 'Arial', sans-serif;
    background-color: white;
    color: #333;
    margin: 0;
    padding: 0;
  }

  h1, h2, h3 {
    color: #0369ef;
    margin-top: 0;
  }
  
  .bl {
    margin-bottom:30px;
  }

  .learning-tracks {
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
    gap: 20px;
  }

  .track {
    background-color: #f4f4f4;
    padding: 20px;
    width: 30%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .track h3 {
    font-size: 22px;
    margin-bottom: 10px;
  }

  .track p {
    font-size: 14px;
    margin-bottom: 20px;
  }

  .track .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #0369ef;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
  }

  .track .button:hover {
    background-color: #024b89;
  }

  .tools {
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
    gap: 20px;
  }

  .tool {
    background-color: #f4f4f4;
    padding: 20px;
    width: 22%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .tool h4 {
    font-size: 20px;
    margin-bottom: 10px;
  }

  .tool p {
    font-size: 14px;
    margin-bottom: 15px;
  }

  .tool .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #0369ef;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
  }

  .tool .button:hover {
    background-color: #024b89;
  }

  .featured-project img {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
</style>
