Azure SQL Database Samples
Copyright (c) Microsoft Corporation
All rights reserved. 
MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ""Software""), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
----------------------------------------------- END OF LICENSE ------------------------------------------

Further Guidance from LCA:  
OSS Engineering Code Management Standards: You must mark and store OSS code in any Microsoft repository or source code depot in accordance with the http://aka.ms/3rdpartyippolicy. You must also comply with any additional code management guidelines established by your engineering group.

Clean Build Requirements. Your release of Microsoft OSS should not include any (a) other existing Microsoft binaries or source code; or (b) third-party binaries or source code unless explicitly authorized by LCA in the OSS request approval.

No Out-of-Scope Releases. Do not add code with features or functionality that is outside the scope of the Microsoft code approved for released by the OSS request approval. If you are unclear as to the scope of the approval, please contact LCA.

Code Scrub: Scrub any comments or personal notes added by your team. In addition, the following items must be removed from the Microsoft OSS: (a) trademarks and trademarked images; (b) developer names; (c) dependencies on external webpages or databases that may break or become inaccessible; and (d) Microsoft product icons (icons should be self-authored).

Distribution in China: Code, products, and services distributed in China must conform to the Mandatory Engineering Policy Chinese GB Certification standards and procedures, even if the code originated from an open source project. (Distributed in China means it was distributed from a physical location (store or server) in China or was delivered from elsewhere pursuant to a contract that applies Chinese law.) Please contact China Certification & Registration Support if you have any questions.

Protocol Documentation:  Protocols implemented in OSS code distributed in Windows, Windows Server, Office, SharePoint Server, Exchange Server or SQL Server that are used to communicate with other Microsoft products must be inventoried.  If OSS code is used as is or if modifications or extensions to the code are contributed back, then protocol documentation will not be required. For questions about Microsoft’s Protocol Policy please contact propolqs@microsoft.com.

Additional Resources: You can find additional guidance and resources on OSS at http://lcaweb/product/OSS/Pages/OSS.aspx.