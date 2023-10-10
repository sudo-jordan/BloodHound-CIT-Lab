# BloodHound CIT Lab

Sample SharpHound data used for an enumeration lab that utilizes BloodHound.

The data used in this lab is derived from [Game of Active Directory](https://github.com/Orange-Cyberdefense/GOAD).

While these are not needed for the lab, some neat resources regarding BloodHound queries can be found at these links:
- https://hausec.com/2019/09/09/bloodhound-cypher-cheatsheet/
- https://github.com/awsmhacks/awsmBloodhoundCustomQueries
- https://phackt.com/pentesting-bloodhound-cypher-queries

<details>
<summary>;)</summary>
  
  `MATCH p=(m:User)-[r:AdminTo]->(n:Computer) RETURN m.name, n.name ORDER BY m.name`
</details>
