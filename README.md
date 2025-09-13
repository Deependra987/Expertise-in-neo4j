# Expertise-in-neo4j
Showcasing my skills and experience with Neo4j, a leading graph database platform. This repository includes projects, queries, data models, and practical implementations demonstrating my ability to design, build, and optimize graph-based solutions using Cypher, data import/export, and graph analytics techniques.
// Create Person nodes
CREATE (alice:Person {name: 'Alice', age: 25})
CREATE (bob:Person {name: 'Bob', age: 30})
CREATE (carol:Person {name: 'Carol', age: 28})

// Create relationships
CREATE (alice)-[:FRIENDS_WITH]->(bob)
CREATE (bob)-[:FRIENDS_WITH]->(carol)
CREATE (carol)-[:FRIENDS_WITH]->(alice);
