<template>
  <div class="font-semibold">
    <div class="pivot-header">
      <button class="self-end justify-self-end border-none ripple-bg-gray-200 rounded-full h-8 w-8 focus:outline-none">
        PS
      </button>
    </div>
    <div class="flex flex-row justify-start bg-blue-700">
      <a class="rounded ripple-bg-blue-700 py-1 px-3 m-1  text-gray-50 cursor-pointer" href="#Allgemein">
        Allgemein
      </a>
      <a class="rounded ripple-bg-gray-200 py-1 px-3 m-1 text-gray-800 cursor-pointer">
        Start
      </a>
      <a class="rounded ripple-bg-blue-700 py-1 px-3 m-1 text-gray-50 cursor-pointer" href="#Ansicht">
        Ansicht
      </a>
      <a class="rounded ripple-bg-blue-700 py-1 px-3 m-1 text-gray-50 cursor-pointer" href="#Projekteinstellungen">
        Projekteinstellungen
      </a>
      <a class="rounded ripple-bg-blue-700 py-1 px-3 m-1 text-gray-50 cursor-pointer" href="#Ausdrucke">
        Ausdrucke
      </a>
    </div>
    <div class="pivot-actions">
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <button class="pivot-button">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 13h6m-3-3v6m5 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
            </svg>
            <span>Neu</span>
          </button>
        </div>
        <span>
          Erstellen
        </span>
      </div>
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <button class="pivot-button">
            <svg class="text-blue-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
            </svg>
            <span>Bearbeiten</span>
          </button>
          <button class="pivot-button">
            <svg class="text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
            <span>Löschen</span>
          </button>
          <div class="pivot-stacked">
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z" />
              </svg>
              <span>Umbenennen</span>
            </button>
            <button>
              <svg class="text-yellow-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z" />
              </svg>
              <span>Zu Favoriten hinzufügen</span>
            </button>
            <button>
              <svg class="text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
              </svg>
              <span>Positionsverlauf löschen</span>
            </button>
          </div>
        </div>
        <span class="text-xs flex justify-center">
          Bearbeiten
        </span>
      </div>
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <div class="pivot-stacked">
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7v8a2 2 0 002 2h6M8 7V5a2 2 0 012-2h4.586a1 1 0 01.707.293l4.414 4.414a1 1 0 01.293.707V15a2 2 0 01-2 2h-2M8 7H6a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2v-2" />
              </svg>
              <span>Kopieren</span>
            </button>
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
              </svg>
              <span>Einfügen</span>
            </button>
            <button>
              <svg class="text-blue-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.121 14.121L19 19m-7-7l7-7m-7 7l-2.879 2.879M12 12L9.121 9.121m0 5.758a3 3 0 10-4.243 4.243 3 3 0 004.243-4.243zm0-5.758a3 3 0 10-4.243-4.243 3 3 0 004.243 4.243z" />
              </svg>
              <span>Ausschneiden</span>
            </button>
          </div>
        </div>
        <span>
          Zwischenablage
        </span>
      </div>
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z" />
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z" />
            </svg>
            <span>Schnittkonstruktionen</span>
          </button>
          <div class="pivot-stacked">
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
              </svg>
              <span>Stückliste berechnen</span>
            </button>
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v11m0 5l4.879-4.879m0 0a3 3 0 104.243-4.242 3 3 0 00-4.243 4.242z" />
              </svg>
              <span>Suchen und Ersetzen</span>
            </button>
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 19a2 2 0 01-2-2V7a2 2 0 012-2h4l2 2h4a2 2 0 012 2v1M5 19h14a2 2 0 002-2v-5a2 2 0 00-2-2H9a2 2 0 00-2 2v5a2 2 0 01-2 2z" />
              </svg>
              <span>Elementverwaltung</span>
            </button>
          </div>
        </div>
        <span>
          Projektfunktionen
        </span>
      </div>
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 4a1 1 0 011-1h16a1 1 0 011 1v2.586a1 1 0 01-.293.707l-6.414 6.414a1 1 0 00-.293.707V17l-4 4v-6.586a1 1 0 00-.293-.707L3.293 7.293A1 1 0 013 6.586V4z" />
            </svg>
            <span>Projektvorgaben</span>
          </button>
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V8a2 2 0 00-2-2h-5m-4 0V5a2 2 0 114 0v1m-4 0a2 2 0 104 0m-5 8a2 2 0 100-4 2 2 0 000 4zm0 0c1.306 0 2.417.835 2.83 2M9 14a3.001 3.001 0 00-2.83 2M15 11h3m-3 4h2" />
            </svg>
            <span>Projektkopf</span>
          </button>
        </div>
        <span>
          Einstellungen
        </span>
      </div>
      <div class="pivot-section">
        <div class="pivot-section-actions">
          <div class="pivot-stacked">
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
              </svg>
              <span>Import</span>
            </button>
            <button>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-8l-4-4m0 0L8 8m4-4v12" />
              </svg>
              <span>Export</span>
            </button>
          </div>
        </div>
        <span>
          Import/Export
        </span>
      </div>
    </div>
  </div>
</template> 

<style scoped>
  @layer components {
    .pivot-header {
      @apply flex flex-row justify-end p-2 bg-blue-700 items-center;
    }

    .pivot-actions {
      @apply flex flex-row justify-start bg-gray-200 text-xs;
    }

    .pivot-section {
      @apply flex flex-col justify-between border-r my-1 px-1 border-gray-400 items-center;
    }

    .pivot-section-actions {
      @apply flex flex-row items-start;
    }

    .pivot-section-actions button {
      @apply flex flex-col px-2 py-1 mx-0.5 xl:p-1 items-center ripple-bg-gray-200 rounded focus:outline-none font-semibold;
    }

    .pivot-section-actions button span {
      @apply xl:hidden;
    }

    .pivot-section-actions button svg {
      @apply h-8 w-8 xl:h-6 xl:w-6;
    }

    .pivot-section-actions .pivot-stacked {
      @apply flex flex-col xl:flex-row;
    }

    .pivot-section-actions .pivot-stacked button {
      @apply flex flex-row;
    }

    .pivot-section-actions .pivot-stacked button span {
      @apply ml-1;
    }

    .pivot-section-actions .pivot-stacked button svg {
      @apply h-4 w-4 xl:w-6 xl:h-6;
    }
  }

</style>

<script setup>
import { defineProps, reactive } from 'vue' 

</script>