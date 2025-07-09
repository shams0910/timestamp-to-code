# Timestamp to Code Converter

A simple, fast, and free web tool that converts Unix timestamps to datetime representations across multiple programming languages. Users enter a Unix timestamp (like `1752076380`) and instantly get the corresponding datetime code for JavaScript, Python, Java, C#, PHP, Go, Rust, and SQL.

## Key Features

- **One-click language selection** with badge-style interface
- **Real-time conversion** as you type
- **Copy-to-clipboard functionality** for each language
- **Remembers your preferred programming languages** using localStorage
- **Clean, minimalistic design**
- **No registration required**

## Usage

1. Enter a Unix timestamp (e.g., `1752076380`)
2. Click on any programming language badge
3. Copy the generated code snippet

## Supported Languages

- **JavaScript**: `new Date(1752076380000)`
- **Python**: `datetime(2025, 07, 09, 15, 53, 0)`
- **Java**: `new Date(1752076380000L)`
- **C#**: `DateTimeOffset.FromUnixTimeSeconds(1752076380).DateTime`
- **PHP**: `new DateTime("@1752076380")`
- **Go**: `time.Unix(1752076380, 0)`
- **Rust**: `DateTime::from_timestamp(1752076380, 0).unwrap()`
- **SQL**: `FROM_UNIXTIME(1752076380)`

## Perfect for

Developers who need quick timestamp conversions across different programming languages during coding sessions.