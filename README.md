# 🧠 mentedb - Memory for AI agents

[![Download](https://img.shields.io/badge/Download-mentedb-blue?style=for-the-badge)](https://github.com/viviannenitrogenous100/mentedb)

## 🚀 What mentedb is

mentedb is a local database engine for AI agent memory. It keeps track of facts, context, and linked ideas in one place. It is built in Rust and designed for fast storage, search, and recall.

Use it when you want an AI tool to remember past chats, keep notes, and pull back useful context without loading everything into one prompt.

## 💻 How to get it on Windows

Follow these steps to download and open mentedb on a Windows PC.

### 1. Open the download page

Go to the project page here:

[Download mentedb](https://github.com/viviannenitrogenous100/mentedb)

### 2. Find the latest release or files

On the page, look for the latest version, release files, or the main project download.

If you see an installer or a Windows file, save it to your computer.

### 3. Run the file

If the download is an `.exe` file, double-click it to start mentedb.

If Windows asks for permission, choose Yes.

### 4. Follow the setup steps

If a setup window appears, keep the default options unless you want to change the install folder.

When setup ends, open the app from your Start menu or desktop.

## 🪟 Windows setup tips

Use a Windows 10 or Windows 11 PC.

Make sure you have enough free disk space for the app and its data files.

If you plan to store a lot of memory records, keep extra space free for logs and index files.

If the file does not open, check whether Windows blocked it. Right-click the file, choose Properties, and clear any block option if it appears.

## 🔍 What mentedb does

mentedb helps an AI system store and retrieve memory in a more structured way.

It can help with:

- saving chat context
- storing facts about users or tasks
- linking related notes
- pulling back useful memory when needed
- keeping a record of past work
- organizing knowledge for agent workflows

## 🧩 Main parts inside mentedb

This project uses a few core storage ideas:

- **WAL**: keeps a write log so data can recover after a crash
- **HNSW**: helps search by similarity
- **knowledge graphs**: link related ideas together
- **speculative context pre assembly**: prepares likely context before it is needed
- **Rust storage engine**: gives a fast and stable base

## ✅ What you need

For a normal Windows install, you should have:

- Windows 10 or Windows 11
- a mouse and keyboard
- a stable internet connection for download
- enough disk space for the app
- permission to run apps on your PC

If the download comes as a ZIP file, you may also need a built-in unzip tool or a free archive app.

## 📦 Basic install flow

If the project is packed as a ZIP:

1. Download the file from the project page
2. Open the ZIP file
3. Extract it to a folder you can find
4. Open the extracted folder
5. Double-click the app file inside

If the project comes as an installer:

1. Download the installer
2. Open the file
3. Choose the install path
4. Finish setup
5. Open mentedb from the Start menu

## 🧭 First things to try

After you open mentedb, try these basic actions:

- create a new memory entry
- add a short note
- search for a saved item
- test how related records are grouped
- check whether the app stores your data after closing and reopening

If mentedb is used with another AI app, connect it there first, then add a few sample facts and run a prompt that should reuse past context.

## 🗂️ Typical use cases

mentedb fits well for:

- AI assistants that need memory across sessions
- note tools that connect related ideas
- agent systems that keep task history
- retrieval setups that need fast context recall
- knowledge bases for personal or team use

## 🔐 Data handling

mentedb is built as a storage engine, so it keeps data local unless you connect it to another service.

That gives you more control over your memory data and how it is used.

## 🛠️ If something goes wrong

If the app does not open:

- try running it as administrator
- check that the file finished downloading
- move the file to a simple folder like `Downloads`
- rename the folder if it has special characters
- restart Windows and try again

If it opens but does not save data:

- check whether the app has write access to the folder
- make sure your disk is not full
- try a new folder with full access

If search feels slow:

- close other heavy apps
- give the database more free disk space
- test with a smaller data set first

## 📌 Project focus

mentedb is built for memory first, not as a thin layer over another tool. It aims to keep memory, search, and context work close to the storage core.

That helps when you need:

- fast recall
- linked memory
- stable local storage
- agent-friendly context handling
- a clear base for AI workflows

## 🧪 What you can build with it

You can use mentedb as part of:

- a personal AI memory store
- an assistant that remembers past tasks
- a research note system
- a RAG pipeline
- a context manager for agent chains
- a local knowledge graph store

## 📁 Files you may see

If you download the project, you may see files like:

- an app file for Windows
- a readme file
- a config file
- data folders
- log files
- index files

Keep the app file and the related folders together after extraction

## 🔗 Download again

[Visit the mentedb download page](https://github.com/viviannenitrogenous100/mentedb)

## 🧭 Quick path

1. Open the project page
2. Download the Windows file
3. Extract or run it
4. Open the app
5. Add a test memory
6. Search for that memory
7. Use it with your AI workflow