# daily_jurnal_app

A new Flutter project.

## Penjelasan Arsitektur

1. Clean Architecture

Models: Representasi data (JournalModel)
Services: Layer untuk komunikasi dengan external services (FirebaseService)
Providers: State management dan business logic (JournalProvider)
UI: Tampilan aplikasi (Screens & Widgets)

2. State Management dengan Riverpod

StateNotifierProvider untuk mengelola state kompleks
Immutable state updates menggunakan copyWith
Reactive UI yang otomatis rebuild saat state berubah

3. Design Pattern

Repository Pattern: firebase bertindak sebagai repository
Provider Pattern: Dependency injection menggunakan Riverpod
Observer Pattern: UI observe perubahan state dari provider


