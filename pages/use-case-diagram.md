```mermaid
%% Mermaid code to replicate the given diagram
%% Define use case diagram type
usecaseDiagram

%% Define actors
actor Developer
actor Hacker
actor User_Recruiter as "User / Recruiter"
actor User_SW as "User / Head SW Engineering"

%% Developer section
Developer --> (IDE & Deployment pipeline)
(IDE & Deployment pipeline) --> (develop application)
(IDE & Deployment pipeline) --> (test application)
(IDE & Deployment pipeline) --> (deploy application)

%% Hacker section
Hacker --> (SW Tools)
(SW Tools) --> (utilize AWS account)
(SW Tools) --> (modify web content)
(SW Tools) --> (deploy malware on end user PC)
(SW Tools) --> (steal data)

%% Trojaner connection from Hacker to SW Tools
(steal data) -.-> (deploy malware on end user PC)
(modify web content) -.-> (deploy malware on end user PC)
(steal data) -.-> (utilize AWS account)

%% User / Recruiter section
User_Recruiter --> (Acrobat Reader)
(Acrobat Reader) --> (check CV)
(Acrobat Reader) --> (check competences)
(Acrobat Reader) --> (contact)

%% User / Head SW Engineering section
User_SW --> (Web browser)

%% Connect sections with dotted lines where applicable
(SW Tools) -.-> (deploy application)
(steal data) -.-> (contact)
(deploy malware on end user PC) -.-> (Web browser)




```