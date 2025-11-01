# GSoC 2025 Final Submission: Microkernel Architecture for Drop-in Plugins

* **Contributor:** Jai Pannu
* **Organization:** The Palisadoes Foundation
* **Project:** Talawa Plugins

---

## 1. Project Summary

This project successfully designed and implemented a microkernel-based, drop-in plugin system for the Talawa ecosystem. The new architecture enables the seamless integration of new features (like payments, analytics, and AI tools) without modifying the core `talawa-api`, `talawa-admin`, or mobile app codebases.

The system includes a dedicated plugin manager to handle plugin discovery, activation, and management. As discussed and agreed upon with my mentors, a streamlined plugin upload functionality and zipping scripts were implemented to provide an easy and secure way for administrators to manage plugins, in place of the originally proposed CDN-backed store.

## 2. Key Deliverables

This project met all its original goals, delivering:

1.  **A Core Microkernel Architecture:** A robust system built into the `talawa-api`, `talawa-admin` and `talawa-mobile` platforms to manage the entire plugin lifecycle.
2.  **Containerization for AI/ML Plugins:** A scalable solution for deploying and managing complex AI models, demonstrated with the T5 Summarizer plugin.
3.  **Three Ready-to-Use Plugins:**
    * **Razorpay Plugin:** A fully functional payment gateway for processing transactions.
    * **Google T5 Summarizer:** An AI plugin (using Hugging Face models) to summarize text content.
    * **Plugin Map for Developers:** A utility plugin to provide a clear map and guide for future community contributors building their own plugins.

## 3. Links to All Pull Requests

All work is categorized by repository, with links to the merged Pull Requests.

### `talawa-api` (Core API, Microkernel, and Endpoints)

* <https://github.com/PalisadoesFoundation/talawa-api/pull/3494>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3514>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3537>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3567>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3606>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3609>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3613>
* <https://github.com/PalisadoesFoundation/talawa-api/pull/3626>

### `talawa-admin` (Microfrontend Extensions in Web)

* <https://github.com/PalisadoesFoundation/talawa-admin/pull/3987>
* <https://github.com/PalisadoesFoundation/talawa-admin/pull/4018>
* <https://github.com/PalisadoesFoundation/talawa-admin/pull/4020>
* <https://github.com/PalisadoesFoundation/talawa-admin/pull/4154>
* <https://github.com/PalisadoesFoundation/talawa-admin/pull/4281>
* <https://github.com/PalisadoesFoundation/talawa-admin/pull/4455>

### `talawa` (Microfrontend Extensions in Mobile)

* <https://github.com/PalisadoesFoundation/talawa/pull/2950>

### `talawa-plugin` (Razorpay, T5 Summarizer, and Plugin Map)

* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/4>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/5>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/8>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/9>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/10>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/16>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/18>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/20>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/23>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/25>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/49>
* <https://github.com/PalisadoesFoundation/talawa-plugin/pull/64>

## 4. Documentation

As part of the project, I also created comprehensive documentation for the new plugin system, guiding both future developers and administrators.

1.  **Plugin Developer Docs:** <https://docs-plugin.talawa.io/docs/>
2.  **Admin Extension Docs:** <https://docs-admin.talawa.io/docs/developer-resources/plugin>
3.  **API Extension Docs:** <https://docs-api.talawa.io/docs/developer-resources/plugin>

---

Thank you to my mentors and The Palisadoes Foundation for this incredible opportunity to contribute to Talawa.
