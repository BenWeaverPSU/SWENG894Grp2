# Architectural Requirements & High-Level Design

| ID      | Architectural Requirement                                                             | Justification                                                                                     |
|---------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| AR-01   | Use frontend/backend architecture with React.js, Express.js, Node.js.                 | Improves maintainability, usability, and scalability.                                               |
| AR-02   | Use RESTful API for backend data interactions.                                        | Supports portability and multiple client interactions.                                              |
| AR-03   | Use PostgreSQL for database.                                                          | Supports structured financial data and meets ACID requirements for reliability.                    |
| AR-04   | Use JWT-based authentication.                                                         | Provides secure, scalable user authentication.                                                      |
| AR-05   | Use role-based access control.                                                        | Enforces permissions between user types.                                                            |
| AR-06   | Support horizontal scaling on backend.                                                | Ensures performance and scalability for 100+ users.                                                 |
| AR-07   | Integrate CI/CD using GitHub Actions.                                                 | Enables fast, reliable deployment and testing, improves maintainability.                            |
| AR-08   | Deploy system on a cloud platform such as Render.                                     | Supports high availability and simplifies deployment and updates.                                   |