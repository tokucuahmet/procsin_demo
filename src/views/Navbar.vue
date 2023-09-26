<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary bold">
      <div class="container-fluid">
        <a class="navbar-brand" href="https://www.procsin.com/">
          <img
            src="https://getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo.svg"
            alt="Bootstrap"
            width="30"
            height="24"
          />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <!-- İçerik Kısmı -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/about">Hakkımızda</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/iconic-seri">İconic Seri</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/en-cok-satanlar">Trend</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/cilt-bakimi">Cilt</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/kisisel-bakim-urunleri">Kişisel Bakım</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/saclar">Saç</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/parfum">Parfüm</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/ev-kozmetigi">Ev Kozmetiği</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/saglıklı-atıstırmalık">Sağlıklı Atıştırmalık</a>
            </li>
          </ul>
          <!-- Arama Kısmı -->
          <form class="d-flex" role="search">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">
              Search
            </button>
          </form>
        </div>
      </div>
    </nav>
    <router-view />
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
