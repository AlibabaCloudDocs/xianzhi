# Crowdsourced Security Testing FAQs {#concept_dcm_rvy_wdb .concept}

## General example of vulnerability submission {#section_pvr_mlq_y2b .section}

The vulnerability resolution submitted by the white hat professionals must contains the following information:

1.  Specify the folder, the line number in the file, and the resolution.
2.  Prepare, if possible, two sets of files, which include files before and after the resolution procedure. Use the `diff` command to obtain the diff file. For example, a content management system \(CMS\) contains an SQL injection vulnerability. The resolution is to escape sensitive characters using `addslashes`. You can provide the following files.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12695/15356536973311_en-US.png)


**Note:** Develop the resolution carefully. The support team of the Crowdsourced Security Testing platform evaluates the completeness of the resolution and the compatibility with the CMS. The details of rewards can be found in the monthly announcement.

## Does the Crowdsourced Security Testing platform disclose my vulnerabilities? {#section_psg_1mq_y2b .section}

The Crowdsourced Security Testing platform keeps the vulnerabilities found in your company confidential. This includes the title, description, and details of the vulnerabilities. Unless otherwise authorized, the Crowdsourced Security Testing platform does not use the vulnerabilities for promotional purposes.

## What if the white-hat testing disrupts my daily operations? {#section_pmw_cmq_y2b .section}

The white hats can be trusted as their identities have been verified by the Crowdsourced Security Testing platform. The vast majority of white hats work hard to help detect potential security risks in a friendly way, and they help you resolve the vulnerabilities. In the unlikely event that white hats cause negative impact by maliciously attacking your system, the Crowdsourced Security Testing support team will work with you to address the issue.

When you use the Crowdsourced Security Testing platform, you should also work on hardening the security protection of your company. Make sure important data is backed up to avoid accidental losses.

## Why are an Alibaba Cloud corporate account and real-name registration required? {#section_k31_hmq_y2b .section}

The real-name registration of the corporate account is an important method the Crowdsourced Security Testing platform uses to verify corporate identities. This prevents others from stealing the corporate identity and collecting system vulnerabilities of the company.

## I use many security products. Why should I join the Crowdsourced Security Testing platform? {#section_z2p_jmq_y2b .section}

Security products are used for the automated scanning and detection of security issues, but they do not offer intelligent scanning. Standardized security risk detection technology is not specifically designed for your business. Issues related to access permission and business logic can rarely be detected by automated security tools. Therefore, human intervention is required.

The white hats detect the security issues from the perspective of attackers. This maximizes the chance of detecting security issues.

## How do I obtain technical support from Alibaba Group Security? {#section_byn_mmq_y2b .section}

While the white hats submit the vulnerabilities and the Crowdsourced Security Testing platform support team reviews them, the Alibaba Group Security Team provides you with a general vulnerability resolution. The Security Team does not know the specific code and logic of the company's business. Therefore, the Security Team can only provide basic resolution proposals and cannot solve the problems completely.

If you require a higher level of security, you can contact the Crowdsourced Security Testing support team to request other security services. Additionally, to form a well-developed security ecosystem, the Crowdsourced Security Testing platform is proactively partnering with third-party security services to provide vulnerability fixing services.

