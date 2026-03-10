# Disable-Data-Consuming-Windows-11-Services

This guide explains how to reduce background internet data usage in Windows 11 by disabling two major services: **Delivery Optimization (DoSvc)** and **Background Intelligent Transfer Service (BITS)**. These services are mainly used by Windows Update and other Microsoft components to download updates and transfer data in the background.

The document shows how to disable **Delivery Optimization** through the Windows Registry and how to stop and disable **BITS** using Administrator Command Prompt commands. After applying these changes, a **system restart is required** to ensure the configuration takes effect.

Disabling these services can help minimize unnecessary background network consumption, which is useful for systems with limited or metered internet connections.
