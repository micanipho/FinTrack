# Software Development Fundamentals - Answer Key

## Section A: Agile Development & Software Engineering Practices
1. **b** - Working with existing codebases and legacy systems
2. **b** - A time-boxed period for completing work
3. **b** - To review and improve team processes
4. **c** - Agile values the items on the right, but values the items on the left more
5. **b** - Identifying and addressing problems early
6. **b** - A brief description of a feature from the user's perspective
7. **b** - To synchronize team activities and identify blockers
8. **b** - Breaking changes being integrated into the main branch frequently
9. **a** - Easier rollback and reduced merge conflicts
10. **b** - Two programmers collaborating on the same code
11. **c** - Changing external API interfaces used by other teams
12. **b** - Shared understanding of work completion criteria
13. **b** - It accumulates in frequently modified, core system components
14. **a** - To define when a user story is complete
15. **b** - A time-boxed research or investigation task
16. **c** - Applied to expensive, time-consuming end-to-end tests that require full system setup
17. **b** - Teams with all skills needed to deliver working software
18. **b** - To visualize remaining work over time
19. **b** - A measure of team productivity over time
20. **b** - Working software provides immediate value and feedback

## Section B: Build Tools & Automation
21. **b** - To automate compilation, testing, and packaging
22. **b** - Maven
23. **b** - Using version ranges (e.g., "1.2.*") for critical security libraries
24. **b** - Consistency and repeatability
25. **b** - The output of a build process (e.g., JAR, WAR files)
26. **b** - Building from scratch, removing previous artifacts
27. **b** - Environmental dependencies or assumptions not captured in the build process
28. **c** - pom.xml
29. **b** - A predefined sequence of build phases
30. **b** - Automated tests are executed
31. **b** - To ensure code quality before deployment
32. **b** - They can change without version number changes, causing inconsistent builds
33. **b** - Cleans, compiles, tests, and installs to local repository
34. **b** - To cache downloaded dependencies locally
35. **a** - Different versions of the same library are required by different dependencies

## Section C: Client/Server Architecture
36. **b** - A distributed computing model with clients requesting services from servers
37. **b** - To provide services and manage resources
38. **b** - To request services and present information to users
39. **b** - A client that performs significant processing locally
40. **b** - A client that relies heavily on server-side processing
41. **b** - Centralized data management and resource sharing
42. **b** - A set of rules for communication between systems
43. **b** - Storing state externally (databases, caches) and passing identifiers in requests
44. **a** - The server maintains information about client sessions
45. **b** - A protocol for transferring web content
46. **b** - For real-time applications where speed is more important than guaranteed delivery
47. **b** - An endpoint for network communication
48. **b** - To identify specific services on a host
49. **b** - The local machine (127.0.0.1)
50. **b** - An error or exception occurs
51. **d** - All of the above
52. **a** - Distributing client requests across multiple servers
53. **a** - A client sends a request and waits for a server response
54. **a** - Software that sits between client and server applications
55. **b** - Achieving consistency while maintaining availability during network partitions

## Section D: Build Pipelines & CI/CD
56. **b** - An automated sequence of steps to build, test, and deploy code
57. **b** - Code commits or pull requests
58. **b** - Automatically building and testing code changes frequently
59. **a** - Automated tests have insufficient coverage or miss critical edge cases
60. **b** - Stop the pipeline and notify the team
61. **b** - Early detection of integration issues
62. **b** - A configured system where applications run (dev, test, prod)
63. **a** - Both environments are not identical in configuration and data
64. **b** - To test applications before production deployment
65. **b** - Managing infrastructure through code and version control
66. **b** - Consistent, reliable, and automated software delivery
67. **b** - Database schema changes are involved and not backward compatible

## Section E: Socket Programming in Java
68. **b** - A software endpoint for network communication
69. **b** - ServerSocket
70. **b** - Socket
71. **b** - accept()
72. **b** - IOException or ConnectException
73. **b** - socket.getInputStream() and socket.getOutputStream()
74. **b** - The entire server thread is blocked, preventing other operations
75. **b** - To free system resources and prevent resource leaks
76. **b** - Thread exhaustion and system crashes under high load
77. **b** - The operation waits until data is available
78. **b** - Frequent timeout exceptions even when data is being transmitted normally
79. **b** - 8000-9999 (common development range)
80. **b** - Proper exception handling and resource cleanup

---
