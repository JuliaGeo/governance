# Charter for the JuliaGeo Organization

This is the organizational charter for the JuliaGeo Organization (the "Organization"). By adding their name to the [Steering Committee.md file](./STEERING-COMMITTEE.md), Steering Committee members (the "members") agree as follows.

## 1. Mission

JuliaGeo is a community interested in effectively and efficiently working with spatial data in Julia. We have various needs and make different contributions to the ecosystem, but collectively we are committed to:

- Developing documented and accessible tools for (geo)spatial data, including vector and raster.
- Providing a coherent workflow linking these tools via adherence to shared interfaces and community standards from both within and outside JuliaGeo.
- Maintaining software for reading and writing (geo)spatial data formats, especially focused on big data and large workloads.
- Communicating spatial data workflows from JuliaGeo and the broader geospatial ecosystem, and making them accessible to the wider scientific and spatial data community.

JuliaGeo packages should be general to geospatial workflows and should not include e.g. domain specific models.

For example, JuliaGeo should include packages like [GDAL.jl](https://github.com/JuliaGeo/GDAL.jl) or [Proj.jl](https://github.com/JuliaGeo/Proj.jl), that wrap commonly used C libraries for their use in computational pipelines for processing spatial data.  But it should not include e.g. a water budgeting tool like [SPAW](https://www.ars.usda.gov/research/software/download/?softwareid=492) - that would be a good user application, but not something that should live in the org.

## 2. Steering Committee

**2.1 Purpose**. The Steering Committee will be responsible for all technical oversight, project approval and oversight, policy oversight, and trademark management for the Organization.

**2.2 Composition**. The Steering Committee voting members are listed in the steering-committee.md file in the repository.
Voting members may be added or removed by no less than 3/4 affirmative vote of the Steering Committee.
The Steering Committee will appoint a Chair responsible for organizing Steering Committee activity.

## 3. Voting

**3.1. Decision Making**. The Steering Committee will strive for all decisions to be made by consensus. While explicit agreement of the entire Steering Committee is preferred, it is not required for consensus. Rather, the Steering Committee will determine consensus based on their good faith consideration of a number of factors, including the dominant view of the Steering Committee and nature of support and objections. The Steering Committee will document evidence of consensus in accordance with these requirements. If consensus cannot be reached, the Steering Committee will make the decision by a vote.

**3.2. Voting**. The Steering Committee Chair will call a vote with reasonable notice to the Steering Committee, setting out a discussion period and a separate voting period. Any discussion may be conducted in person or electronically by text, voice, or video. The discussion will be open to the public. In any vote, each voting representative will have one vote. Except as specifically noted elsewhere in this Charter, decisions by vote require a simple majority vote of all voting members.

## 4. Termination of Membership

In addition to the method set out in section 2.2, the membership of a Steering Committee member will terminate if any of the following occur:

**4.1 Resignation**. Written notice of resignation to the Steering Committee.

**4.2 Unreachable Member**. If a member is unresponsive at its listed handle for more than three months the Steering Committee may vote to remove the member.

## 5. No Confidentiality

Information disclosed in connection with any of the Organization's activities, including but not limited to meetings, Contributions, and submissions, is not confidential, regardless of any markings or statements to the contrary.

## 6. Project Criteria

In order to be eligible to be a Organization project, a project must:

* Be approved by the Steering Committee.
* Agree to follow the guidance and direction of the Steering Committee.
* Use only the following outbound licenses or agreements unless otherwise approved:
  - For code, the [MIT license](https://opensource.org/license/mit), or a similarly permissive license (ISC, BSD-3, Apache-2.0).
  - For data, a license on the Open Knowledge Foundation's list of [Recommended Conformant Licenses](http://opendefinition.org/licenses/).
  - For specifications, a community developed and maintained specification agreement, such the [Open Web Foundation Agreements](https://www.openwebfoundation.org/the-agreements) or [Community Specification Agreement](https://github.com/CommunitySpecification/1.0).
* Include and adhere to the Organization's policies, including the [trademark policy](./TRADEMARKS.md) and the [code of conduct](./CODE-OF-CONDUCT.md).

## 7. Amendments

Amendments to this charter, the [trademark policy](./TRADEMARKS.md), or the [code of conduct](./CODE-OF-CONDUCT.md) may only be made with at least a 3/4 affirmative vote of the Steering Committee.

---
Adapted from https://github.com/github/MVG. Licensed under the [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).
