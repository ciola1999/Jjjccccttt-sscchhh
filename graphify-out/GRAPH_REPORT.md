# Graph Report - web-desktop  (2026-10-24)

## Corpus Check
- 862 files · ~922,773 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 352 file(s) not represented in the graph (top: .toml 341, (none) 5, .ico 2)

## Summary
- 8356 nodes · 31292 edges · 203 communities (190 shown, 13 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 167 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `d18cccd3`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- toApiErrorResponse
- CommandError
- isDesktopRuntime
- Modal
- ApiRequestError
- sync-status.ts
- database-endpoint.ts
- billing.rs
- validations/inventory.ts
- siswa/page.tsx
- ref_bun_test
- pesanGalat
- api-response.ts
- presensi-kelas/page.tsx
- services/billing.ts
- accounting.rs
- academic.rs
- turso.rs
- TursoClient
- pmb-dapodik.ts
- services/accounting.ts
- operational.rs
- InventarisWorkspace.tsx
- services/berkas-sekolah.ts
- next
- services/wa-notification.ts
- nilai_akhir.rs
- payroll/commands.rs
- authorize.ts
- face-liveness.ts
- loan.rs
- KeuanganWorkspace.tsx
- id-card-renderer.ts
- tutup_buku.rs
- sync.rs
- auth/password-reset.ts
- uks.rs
- scanner.rs
- class_attendance.rs
- time_policy.rs
- inventory.rs
- administration.rs
- payroll-recap.ts
- UksWorkspace.tsx
- scanner/page.tsx
- grades.rs
- desktop-session-store.ts
- rapel.rs
- wa_notification.rs
- Icon
- db-migrations.ts
- two-factor/route.ts
- attendance-processor.ts
- server/license.ts
- services/loan.ts
- hari-kerja.ts
- services/tutup-buku.ts
- request-security.ts
- JsonBodyError
- .ensure_schema
- license.rs
- siswa_dapodik.rs
- shifts/route.ts
- content-admin.ts
- face_match.rs
- kickDesktopSync
- time-policy.ts
- secrets.rs
- storage.rs
- services/payroll-rapel.ts
- saveFileWithPicker
- face-match.ts
- services/nilai-akhir.ts
- personnel-import.ts
- services/counseling.ts
- useAuth
- fixture
- setup_state
- portability.rs
- sql_backend.rs
- operators/page.tsx
- services/correction.ts
- MailSettingsCard.tsx
- csp
- erapor.ts
- gateways/grades.ts
- berkas_sekolah.rs
- TursoConfig
- KasbonWorkspace.tsx
- wa_sender.rs
- validations/class-attendance.ts
- validations/nilai-akhir.ts
- attendance_dashboard.rs
- scripts
- database-config.ts
- gateways/password-reset-history.ts
- konten_gambar.rs
- wa-sender.ts
- validate_mutation
- package.json
- visual-store.ts
- invalid
- Value
- operator-admin.ts
- DeviceProfileCard.tsx
- engine.rs
- dependencies
- @playwright/test
- services/holiday-whitelist.ts
- queue_wali_notification_tx
- bootstrap.ts
- AttendanceGauge3D.tsx
- notifikasi-wa/page.tsx
- PayrollCalculator
- ip-allowlist.ts
- grades/delete/route.ts
- super
- pmb_bayar.rs
- compilerOptions
- Value
- save_item
- ekspor.ts
- attendance-photos/query/route.ts
- DecisionReason
- TiltCard.tsx
- gateways/license.ts
- types/pmb.ts
- PageContentManager.tsx
- AudioSynthesizer
- gateways/password-reset.ts
- biome.json
- devDependencies
- migrate-old-db.ts
- bel-perangkat.ts
- impor-dapodik.ts
- database-promotion.ts
- riwayat-reset-password/page.tsx
- payroll_seed.rs
- run-tests.ts
- face-template/route.ts
- resolve_bootstrap_turso_config
- DapodikSiswa.tsx
- detail/route.ts
- types/accounting.ts
- AttendanceGaugeGate.tsx
- PayrollStatus
- SPPG App - Tech Stack & Architecture Rules
- SPPG Attendance Fullstack Development Skill & Knowledge Base
- build.rs
- employee-identity.ts
- attendance_ledger.rs
- test-data.ts
- Zero-Error & Zero-Warning Code Standards
- next.config.ts
- Absensi SPPG
- jp/route.ts
- license.test.ts
- default.json
- .baca_keadaan_bayar_pmb
- attendance-photos/route.ts
- database-retry.ts
- assert_offline_login_allowed
- Value
- PengaturanNilai.tsx
- json
- whitelist/route.ts
- save-portal/route.ts
- shift/page.tsx
- siapkan-berkas.ts
- security-mutation.ts
- validations/siswa-dapodik.ts
- RowAction
- build
- deserialize
- setup/page.tsx
- baca_slip
- android-bridge.d.ts
- postcss.config.mjs
- sumber/README.md
- manajemen_sekolah_desktop
- parse_wa_switches
- images/query/route.ts
- recipients/route.ts
- .as_str
- DataDapodikPmb.tsx
- Value
- createBrandingMirror
- queue_wali_notification_tx
- grades/query/route.ts
- wali-credentials/route.ts
- company-profile/route.ts
- .save_article
- compose_from_stored
- loans/route.ts
- opname-history/route.ts
- undefer/route.ts
- uks/delete/route.ts
- get_jp_settings

## God Nodes (most connected - your core abstractions)
1. `CommandError` - 988 edges
2. `DesktopState` - 698 edges
3. `ensureServerDatabaseInitialized()` - 637 edges
4. `toApiErrorResponse()` - 505 edges
5. `noStoreJson()` - 504 edges
6. `assertSameOriginMutation()` - 480 edges
7. `requireWebPermission()` - 472 edges
8. `isDesktopRuntime()` - 389 edges
9. `getServerDatabase()` - 369 edges
10. `readJsonBody()` - 316 edges

## Surprising Connections (you probably didn't know these)
- `5. Gateway Pattern & Runtime Abstraction` --references--> `isDesktopRuntime()`  [INFERRED]
  .agents/rules/tech-stack-architecture.md → src/lib/runtime/app-runtime.ts
- `B. Next.js, Tauri v2 Static Export & Bun Test Gotchas` --references--> `AutoAlfaRunner()`  [INFERRED]
  .agents/skills/sppg-fullstack/SKILL.md → src/components/AutoAlfaRunner.tsx
- `Manajemen Sekolah - Core Engineering Rules` --references--> `Modal()`  [INFERRED]
  AGENTS.md → src/components/ui/Modal.tsx
- `3. Ironclad Backend Logic, Data Security & Sync Integrity` --references--> `triggerGenerateAlfa()`  [INFERRED]
  .agents/skills/sppg-fullstack/SKILL.md → src/lib/gateways/alfa.ts
- `Manajemen Sekolah - Core Engineering Rules` --references--> `isDesktopRuntime()`  [INFERRED]
  AGENTS.md → src/lib/runtime/app-runtime.ts

## Import Cycles
- 1-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/config.rs`
- 1-file cycle: `src-tauri/src/desktop/storage.rs -> src-tauri/src/desktop/storage.rs`
- 1-file cycle: `src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/sync.rs`
- 1-file cycle: `src-tauri/src/desktop/administration.rs -> src-tauri/src/desktop/administration.rs`
- 1-file cycle: `src-tauri/src/desktop/commands.rs -> src-tauri/src/desktop/commands.rs`
- 1-file cycle: `src-tauri/src/desktop/class_attendance.rs -> src-tauri/src/desktop/class_attendance.rs`
- 1-file cycle: `src-tauri/src/desktop/secrets.rs -> src-tauri/src/desktop/secrets.rs`
- 1-file cycle: `src-tauri/src/desktop/payroll/commands.rs -> src-tauri/src/desktop/payroll/commands.rs`
- 1-file cycle: `src-tauri/src/desktop/operational.rs -> src-tauri/src/desktop/operational.rs`
- 1-file cycle: `src-tauri/src/desktop/scanner.rs -> src-tauri/src/desktop/scanner.rs`
- 1-file cycle: `src-tauri/src/desktop/payroll/engine.rs -> src-tauri/src/desktop/payroll/engine.rs`
- 2-file cycle: `src-tauri/src/desktop/sql_backend.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/sql_backend.rs`
- 2-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/secrets.rs -> src-tauri/src/desktop/config.rs`
- 2-file cycle: `src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/sync.rs`
- 2-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/config.rs`
- 3-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/rapel.rs -> src-tauri/src/desktop/config.rs`
- 3-file cycle: `src-tauri/src/desktop/rapel.rs -> src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/rapel.rs`
- 3-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/config.rs`
- 4-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/secrets.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/rapel.rs -> src-tauri/src/desktop/config.rs`
- 4-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/turso.rs -> src-tauri/src/desktop/rapel.rs -> src-tauri/src/desktop/config.rs`

## Communities (203 total, 13 thin omitted)

### Community 0 - "toApiErrorResponse"
Cohesion: 0.02
Nodes (296): next, runtime, POST(), runtime, POST(), runtime, bodySchema, POST() (+288 more)

### Community 1 - "CommandError"
Cohesion: 0.03
Nodes (349): cancel_backup(), delete_attendance(), delete_backup(), selaraskan_status_backup(), delete_class_attendance(), delete_lesson_period(), get_class_attendance_detail(), get_roster_for_attendance() (+341 more)

### Community 2 - "isDesktopRuntime"
Cohesion: 0.03
Nodes (175): OperationalPage(), Tab, GELOMBANG_KOSONG, PmbPage(), bukaDetail(), hapusPendaftar(), promosikan(), setelahBayarBerubah() (+167 more)

### Community 3 - "Modal"
Cohesion: 0.05
Nodes (96): react-dom, EMPTY_DRAFT, formatDisplayDate(), HolidaysPage(), BpjsRulesPage(), IDR, IDR, JpRatesPage() (+88 more)

### Community 4 - "ApiRequestError"
Cohesion: 0.02
Nodes (208): POST(), POST(), POST(), runtime, POST(), runtime, POST(), POST() (+200 more)

### Community 5 - "sync-status.ts"
Cohesion: 0.05
Nodes (76): BimbinganKonselingPage(), LoginPage(), BrandLink(), getSnapshot(), listeners, scrollActiveLinkIntoView(), SERVER_STATE, SidebarNav() (+68 more)

### Community 6 - "database-endpoint.ts"
Cohesion: 0.24
Nodes (11): RFC-1918, DATABASE_PROVIDER_OPTIONS, DatabaseEndpointIssue, DatabaseEndpointReview, DatabaseProviderOption, isDatabaseProvider(), isPrivateIpv4(), isPrivateNetworkHost() (+3 more)

### Community 7 - "billing.rs"
Cohesion: 0.03
Nodes (153): account(), AKUN_PIUTANG_SISWA, AKUN_TITIPAN_WALI, alokasi_pembayaran(), antre_pengingat(), assert_titipan_utuh(), aturan_pembayaran(), baris_jurnal_pembayaran() (+145 more)

### Community 8 - "validations/inventory.ts"
Cohesion: 0.03
Nodes (142): barangDilacak(), buatUnit(), cancelMutation(), canonicalTempat(), documentInventaris(), Executor, insertMutasiStatement(), jumlahKembali() (+134 more)

### Community 9 - "siswa/page.tsx"
Cohesion: 0.05
Nodes (100): react, GuruPage(), ActiveTab, BuilderPanel, DEFAULT_ID_CARD_ELEMENTS, IdCardsPage(), LayoutPanel, KaryawanPage() (+92 more)

### Community 10 - "ref_bun_test"
Cohesion: 0.04
Nodes (41): @libsql/client, MODELS, source, target, databasePath, workDir, DRAFT, DATABASE_KEYS (+33 more)

### Community 11 - "pesanGalat"
Cohesion: 0.05
Nodes (108): pesanGalat(), buatKuitansiPdf(), cetakKuitansi(), esc(), keteranganMetode(), namaAlokasi(), tanggalPanjang(), teksKuitansiWa() (+100 more)

### Community 12 - "api-response.ts"
Cohesion: 0.05
Nodes (32): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+24 more)

### Community 13 - "presensi-kelas/page.tsx"
Cohesion: 0.10
Nodes (43): PresensiKelasPage(), TabKey, HARI, JadwalDraft, JadwalPanel(), JadwalPanelProps, BelSekolahRunner(), sudahBerbunyi (+35 more)

### Community 14 - "services/billing.ts"
Cohesion: 0.04
Nodes (119): account(), assertTitipanUtuh(), batalPembayaranTx(), Calon, cancel(), cancelPayment(), catatPembayaranTx(), discounts() (+111 more)

### Community 15 - "accounting.rs"
Cohesion: 0.05
Nodes (91): akun_bawaan(), akun_json(), akun_nonaktif_dan_kode_ganda_ditolak(), AkunBawaan, AkunDraft, AkunLama, AkunSaldo, AkunValid (+83 more)

### Community 16 - "academic.rs"
Cohesion: 0.05
Nodes (90): assert_unique_value(), assert_unit_exists(), baca_wali_kredensial(), backfill_missing_id_cards(), bulk_issue_wali_passwords(), cache_personnel_photo_local(), chosen_shift(), CLASS_USAGE (+82 more)

### Community 17 - "turso.rs"
Cohesion: 0.03
Nodes (66): ADMIN_DEFAULT_EXCLUDED_PERMISSIONS, assert_attendance_precondition(), assert_operator_deletable(), attendance_session_of(), AttendanceGuardRow, BASE32_ALPHABET, base32_decoding_forgives_human_typing(), bentrok_id_unik_ditahan_dengan_pesan_yang_sama_dengan_web() (+58 more)

### Community 18 - "TursoClient"
Cohesion: 0.07
Nodes (9): MailFailure, normalize_recovery_code(), OperatorTotp, random_request_id(), reset_error(), sha256_hex(), TursoClient, .RECOVERY_CODE_COUNT (+1 more)

### Community 19 - "pmb-dapodik.ts"
Cohesion: 0.09
Nodes (34): AGAMA, ALAT_TRANSPORTASI, angka(), DataDapodik, dataDapodikDasarSchema, dataDapodikSchema, digit(), isianWajibDapodik() (+26 more)

### Community 20 - "services/accounting.ts"
Cohesion: 0.06
Nodes (71): assertAkunAktif(), assertRentang(), BarisTulis, Executor, getJournal(), ledger(), listJournals(), newId() (+63 more)

### Community 21 - "operational.rs"
Cohesion: 0.07
Nodes (72): assert_employee_identity_free(), assert_whitelist_unique(), base_revision(), copy_to_public_dir(), create_employee(), create_holiday(), create_holiday_whitelist(), create_holidays_bulk() (+64 more)

### Community 22 - "InventarisWorkspace.tsx"
Cohesion: 0.05
Nodes (92): @zxing/browser, cetakBeritaAcara(), cetakLabelBarang(), esc(), isi(), kop(), LABEL_PER_LEMBAR, selisih() (+84 more)

### Community 23 - "services/berkas-sekolah.ts"
Cohesion: 0.15
Nodes (24): BerkasKiriman, BerkasSekolah, berkasSekolahSchema, JENIS_BERKAS_SEKOLAH, JenisBerkasSekolah, LABEL_JENIS_BERKAS, MAKS_BASE64_BERKAS, MAKS_BYTE_BERKAS (+16 more)

### Community 24 - "next"
Cohesion: 0.03
Nodes (99): zod, POST(), runtime, POST(), runtime, POST(), runtime, POST() (+91 more)

### Community 25 - "services/wa-notification.ts"
Cohesion: 0.09
Nodes (46): CONTOH, cancelWaNotification(), getWaConfig(), getWaTemplates(), listWaNotifications(), saveWaConfig(), saveWaTemplates(), SqlExecutor (+38 more)

### Community 26 - "nilai_akhir.rs"
Cohesion: 0.06
Nodes (67): bahan_erapor_dari_rekap_n2(), BarisTahunAjaran, bobot_kehadiran(), bobot_sah(), BobotJenis, bulat_akhir(), cloud_grade_type_values(), CLOUD_UPSERT_GRADE_TYPE_SQL (+59 more)

### Community 27 - "payroll/commands.rs"
Cohesion: 0.06
Nodes (61): APPLIES_TO_ALL, APPLIES_TO_GROUP_PREFIXES, bpjs_rule_id(), desktop_create_payroll_run(), desktop_delete_bpjs_rule(), desktop_delete_jp_rate(), desktop_delete_overtime_rule(), desktop_delete_payroll_component() (+53 more)

### Community 28 - "authorize.ts"
Cohesion: 0.03
Nodes (71): POST(), runtime, runtime, POST(), runtime, runtime, POST(), runtime (+63 more)

### Community 29 - "face-liveness.ts"
Cohesion: 0.07
Nodes (55): LivenessCapture(), LivenessCaptureProps, LivenessCaptureResult, Phase, SCAN_PHOTO_HEIGHT, SCAN_PHOTO_MIME, SCAN_PHOTO_QUALITY, SCAN_PHOTO_WIDTH (+47 more)

### Community 30 - "loan.rs"
Cohesion: 0.05
Nodes (69): aktif(), AKUN_BEBAN_BPJS, AKUN_BEBAN_GAJI, AKUN_KAS, AKUN_PIUTANG_KARYAWAN, AKUN_POTONGAN_GAJI, AKUN_UTANG_BPJS, AKUN_UTANG_PPH21 (+61 more)

### Community 31 - "KeuanganWorkspace.tsx"
Cohesion: 0.06
Nodes (71): jspdf, jspdf-autotable, hariIniWib(), akunBaris(), BarisTabel, buatLebarPdf(), buatTabelPdf(), BULAN_PENDEK (+63 more)

### Community 32 - "id-card-renderer.ts"
Cohesion: 0.07
Nodes (64): qrcode, BuilderPanel(), BuilderPanelProps, LayoutPanel(), LayoutPanelProps, buildCustomLayoutCss(), buildCustomPrintHtml(), bungkusTeks() (+56 more)

### Community 33 - "tutup_buku.rs"
Cohesion: 0.06
Nodes (59): ALASAN_PEMBERITAHUAN_MATI, ALASAN_SINKRON_BASI, antre_pemberitahuan(), assert_periode_terbuka(), baca_tutup(), banding_saldo(), baris_json(), batas_tutup() (+51 more)

### Community 34 - "sync.rs"
Cohesion: 0.09
Nodes (53): APPEND_ONLY_TABLES, APPEND_PULL_LIMIT, apply_push_results(), apply_snapshot(), apply_snapshot_self_heals_a_stale_local_schema_missing_a_snapshot_table(), assert_cloud_schema_compatible(), CANONICAL_SYNC_ROUTES, DEVICE_LOCAL_SETTING_KEYS (+45 more)

### Community 35 - "auth/password-reset.ts"
Cohesion: 0.08
Nodes (53): errorResponse(), okResponse(), POST(), ResetBody, ResetStep, runtime, text(), checkLoginRateLimit() (+45 more)

### Community 36 - "uks.rs"
Cohesion: 0.08
Nodes (50): adopt_visit(), BukaDraft, BukaValid, butuh_koneksi(), butuh_salinan(), clean(), closed_and_synced_copies_are_pruned_after_thirty_days(), closing_queues_one_wali_message_only_when_switched_on() (+42 more)

### Community 37 - "scanner.rs"
Cohesion: 0.07
Nodes (53): AttendanceState, Backup, current_jakarta_moment(), decision_log(), describe_addresses(), detect_device_ip_addresses(), distance_meters(), Employee (+45 more)

### Community 38 - "class_attendance.rs"
Cohesion: 0.06
Nodes (41): atur_jam_selesai_bel(), atur_nomor_jam_bel(), BOLOS_BAWAAN, class_status(), configured_jp_max(), dasar(), DEFAULT_JP_DURATION_MINUTES, DEFAULT_JP_MAX_PER_DAY (+33 more)

### Community 39 - "time_policy.rs"
Cohesion: 0.07
Nodes (59): add_days(), alfa_generation_minute(), batas_pulang_tidak_memperpanjang_hari_shift_fleksibel(), calculate_normal_work_minutes(), calculate_work(), calculate_work_on_timeline(), check_in_minute_on_shift_timeline(), checkout_without_entry_needs_verification() (+51 more)

### Community 40 - "inventory.rs"
Cohesion: 0.03
Nodes (50): ALASAN_FORMULIR, ALASAN_MUTASI, ascii_lower(), AturanUnit, build_cancellation(), build_cancellation_swaps_sides(), cancellation_id(), CLOUD_INSERT_MUTATION_SQL (+42 more)

### Community 41 - "administration.rs"
Cohesion: 0.06
Nodes (76): attendance_events(), attendance_json(), backup_bentrok_dan_shift_tidak_ada_ditolak(), clean_time(), clock_duration(), create_backup(), create_backup_and_correction_workflow_in_rust(), create_correction() (+68 more)

### Community 42 - "payroll-recap.ts"
Cohesion: 0.07
Nodes (55): normalizePersonnelRole(), pinjamanAktif(), applyOvertimePolicy(), BpjsBreakdownEntry, BpjsRule, calculateBpjs(), calculateComponents(), calculateOvertimeIndex() (+47 more)

### Community 43 - "UksWorkspace.tsx"
Cohesion: 0.07
Nodes (65): BarisHitung, BarisObat(), BarisObatState, Feedback, FormBuka(), FormSimpan(), galatDenganSinkron(), jamSekarangWib() (+57 more)

### Community 44 - "scanner/page.tsx"
Cohesion: 0.08
Nodes (44): @tauri-apps/api, @vladmandic/human, ScanLogItem, ScannerPage(), BulkEnrollModal(), CameraEnrollModal(), Filter, jenisLabel() (+36 more)

### Community 45 - "grades.rs"
Cohesion: 0.17
Nodes (18): assessment_list_query(), daftar_penilaian_semua_rombel_dan_filter_jenis(), delete_assessment(), get_assessment(), id_nilai_selalu_berbeda_meski_dibuat_beruntun(), integer(), JENIS_PENILAIAN, jenis_saringan() (+10 more)

### Community 46 - "desktop-session-store.ts"
Cohesion: 0.07
Nodes (36): metadata, RootLayout(), DesktopLoginResponse, DesktopSessionMode, DesktopSessionSnapshot, emit(), getDesktopSessionServerSnapshot(), getDesktopSessionSnapshot() (+28 more)

### Community 47 - "rapel.rs"
Cohesion: 0.06
Nodes (48): BarisSlip, BATAL_RAPEL_SQL, bulan_ke(), bulat(), CALC_TYPE_RAPEL, calon(), cancel(), CLOUD_CANCEL_RAPEL_SQL (+40 more)

### Community 48 - "wa_notification.rs"
Cohesion: 0.06
Nodes (30): ambang_alfa_diurai_sesuai_vektor_typescript(), DEFAULT_AMBANG_ALFA_DAYS, DEFAULT_AMBANG_ALFA_LIMIT, DEFAULT_PENGINGAT_HARI_LEWAT, DEFAULT_PENGINGAT_HARI_SEBELUM, MAX_AMBANG_ALFA_DAYS, MAX_AMBANG_ALFA_LIMIT, MAX_PENGINGAT_HARI_SEBELUM (+22 more)

### Community 49 - "Icon"
Cohesion: 0.06
Nodes (60): DashboardPage(), loadOverviewData(), formatDisplayDateTime(), formatMinutesToHours(), formatTimeOnly(), getFirstDayOfMonth(), getRelativeDate(), HistoryPage() (+52 more)

### Community 50 - "db-migrations.ts"
Cohesion: 0.08
Nodes (39): AccessSubject, base64ToBytes(), bytesToBase64(), constantTimeEqual(), derivePassword(), hashPasswordValue(), hashVerifiedPasswordForUpgrade(), verifyPassword() (+31 more)

### Community 51 - "two-factor/route.ts"
Cohesion: 0.09
Nodes (46): Manajemen Sekolah - Core Engineering Rules, This is NOT the Next.js you know, assertPasswordSaatIni(), POST(), runtime, TwoFactorBody, TwoFactorStep, buildOtpAuthUri() (+38 more)

### Community 52 - "attendance-processor.ts"
Cohesion: 0.08
Nodes (45): ExplicitInstant, ATTENDANCE_SOURCE_VALUES, AttendanceSource, DEFAULT_ATTENDANCE_SOURCE, PERSONNEL_ROLES, PersonnelRole, ScanResult, addDays() (+37 more)

### Community 53 - "server/license.ts"
Cohesion: 0.12
Nodes (28): checkInstallableLicense(), compactLicenseText(), evaluateWebLicense(), expiredMessage(), instanceCodeFromId(), invalidateLicenseCache(), isCalendarDate(), isWebsiteHost() (+20 more)

### Community 54 - "services/loan.ts"
Cohesion: 0.08
Nodes (51): assertAkunBayar(), balikJurnalTx(), barisDua(), catatMutasiTx(), catatPembayaranPayrollTx(), decideLoan(), deferLoan(), Executor (+43 more)

### Community 55 - "hari-kerja.ts"
Cohesion: 0.06
Nodes (60): EksporLaporanKehadiran(), hariIniWib(), LABEL_JENIS, LiburMassalDialog(), Tab, tanggalPanjang(), formatJamOperasional(), formatTimestampOperasional() (+52 more)

### Community 56 - "services/tutup-buku.ts"
Cohesion: 0.10
Nodes (51): isValidOperatorPhone(), normalizeOperatorPhone(), generateAlfaHarian(), antrePengingatTx(), saveClassAttendance(), assertPeriodeTerbuka(), bacaTutup(), barisTutup() (+43 more)

### Community 57 - "request-security.ts"
Cohesion: 0.07
Nodes (38): bodySchema, POST(), runtime, errorResponse(), LoginBody, POST(), runtime, DELETE() (+30 more)

### Community 58 - "JsonBodyError"
Cohesion: 0.52
Nodes (3): JsonBodyError, readBoundedBody(), readBoundedJsonBody()

### Community 59 - ".ensure_schema"
Cohesion: 0.13
Nodes (24): antrean_wa_cloud_menolak_dedupe_ganda_lintas_perangkat(), apply_event_to_turso(), bootstrap_lalu_login_berhasil_tanpa_jaringan(), BootstrapStatus, insert_log_if_missing(), insert_payroll_audit_log(), izin_admin_yang_dicabut_tidak_hidup_lagi_setelah_provisioning_ulang(), kode_pemulihan_mengembalikan_akses_tanpa_jaringan() (+16 more)

### Community 60 - "license.rs"
Cohesion: 0.04
Nodes (95): android_device_label(), android_id(), android_property(), base_payload(), bootstrap_license_text(), BUILD_DATE, check_installable(), compact_license_text() (+87 more)

### Community 61 - "siswa_dapodik.rs"
Cohesion: 0.08
Nodes (39): AGAMA, ALAT_TRANSPORTASI, Aturan, Angka, Digit, Email, Hp, Pilihan (+31 more)

### Community 62 - "shifts/route.ts"
Cohesion: 0.08
Nodes (39): DELETE(), HolidayMutationBody, parseDraft(), PATCH(), POST(), runtime, DELETE(), OperatorMutationBody (+31 more)

### Community 63 - "content-admin.ts"
Cohesion: 0.18
Nodes (22): ArticleManager(), ambilDetailArtikel(), daftarArtikel(), hapusArtikel(), simpanArtikel(), buatIdBerita(), ContentNotFoundError, deleteArticle() (+14 more)

### Community 64 - "face_match.rs"
Cohesion: 0.09
Nodes (35): a(), b(), c(), cloud_template_values(), CLOUD_UPSERT_TEMPLATE_SQL, decode_face_vector(), FACE_MODEL_ID, face_settings() (+27 more)

### Community 65 - "kickDesktopSync"
Cohesion: 0.05
Nodes (79): AkademikPage(), JadwalPanel, JamPelajaranCard, JurusanPanel, MapelPanel, ModalKey, PenugasanPanel, RombelPanel (+71 more)

### Community 66 - "time-policy.ts"
Cohesion: 0.09
Nodes (40): addCalendarDays(), assertNonNegativeInteger(), assertPolicyMinutes(), AturanJamKerja, AturanJendelaMasuk, AturanShiftDariJam, calendarDayDifference(), DecideTimeScanInput (+32 more)

### Community 67 - "secrets.rs"
Cohesion: 0.10
Nodes (33): clear_turso_config(), CLIENT_ID, corrupted_salt_is_rejected_without_trusting_the_snapshot(), CREDENTIAL_KEY, credential_paths(), delete_os_vault_secret(), derive_key(), derive_turso_key() (+25 more)

### Community 68 - "storage.rs"
Cohesion: 0.12
Nodes (37): ATTENDANCE_SOURCE_VALUES, audit(), clear_login_failures(), CLOUD_MIRRORED_TABLES, database(), DATABASE_NAME, device_identity_is_local_and_stable(), DEVICE_OWNED_TABLES (+29 more)

### Community 69 - "services/payroll-rapel.ts"
Cohesion: 0.09
Nodes (41): bulanWib(), DialogCari(), hitung(), setujui(), Feedback, KETERANGAN_STATUS, hitungCalonRapel(), simpanRapel() (+33 more)

### Community 70 - "saveFileWithPicker"
Cohesion: 0.07
Nodes (45): ambilDetail(), angka(), eksporLaporanKehadiran(), teks(), bacaImporBarang(), EksporErapor(), angka(), catatanBolos() (+37 more)

### Community 71 - "face-match.ts"
Cohesion: 0.09
Nodes (29): KeamananAbsensiCardProps, decodeFaceVector(), FACE_MODES, FACE_TEMPLATE_MAX_SAMPLES, FACE_TEMPLATE_SOURCES, FACE_THRESHOLD_MAX, FACE_THRESHOLD_MIN, FACE_VECTOR_DIM (+21 more)

### Community 72 - "services/nilai-akhir.ts"
Cohesion: 0.12
Nodes (38): BarisJenis, bobotKehadiran(), config(), deleteType(), duaDesimal(), erapor(), Executor, galat() (+30 more)

### Community 73 - "personnel-import.ts"
Cohesion: 0.11
Nodes (41): downloadEmployeeTemplate(), exportEmployees(), HEADERS, readEmployeeWorkbook(), downloadStudentTemplate(), downloadTeacherTemplate(), exportStudents(), exportTeachers() (+33 more)

### Community 74 - "services/counseling.ts"
Cohesion: 0.11
Nodes (25): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+17 more)

### Community 75 - "useAuth"
Cohesion: 0.05
Nodes (103): 3. Ironclad Backend Logic, Data Security & Sync Integrity, AuditAbsensiPage(), FILTER_OPTIONS, FilterKeparahan, formatTanggalPanjang(), KEPARAHAN_LABEL, KEPARAHAN_TONE, skorTone() (+95 more)

### Community 76 - "fixture"
Cohesion: 0.15
Nodes (36): aktifkan(), attendance_log_and_outbox_are_rolled_back_together(), daftar_ip_kosong_tidak_membatasi_scan(), daftar_ip_terisi_menolak_alamat_di_luar_daftar(), desktop_geofence_rejection_is_logged_without_attendance(), duplicate_is_logged_without_changing_daily_attendance(), ejaan_jenis_personil_huruf_besar_tetap_dikenali_sebagai_siswa(), fitur_foto_mati_membuat_sakelar_role_tidak_berlaku() (+28 more)

### Community 77 - "setup_state"
Cohesion: 0.14
Nodes (34): automatic_codes_are_sequential_per_prefix(), cancellation_is_idempotent_and_guards_consumed_stock(), decimal_items_lock_after_history_and_round_procurement_value(), document(), document_groups_by_number_and_skips_cancelled_rows(), duplicate_codes_from_offline_devices_are_flagged(), expirable_batches_follow_their_own_id(), expirable_return_goes_back_to_its_batch() (+26 more)

### Community 78 - "portability.rs"
Cohesion: 0.09
Nodes (26): backup_file_name(), BACKUP_MAGIC, berkas_terenkripsi_bolak_balik_utuh(), buat_hub(), database_asing_ditolak_sebelum_menimpa_apa_pun(), decrypt_backup(), derive_backup_key(), encrypt_backup() (+18 more)

### Community 79 - "sql_backend.rs"
Cohesion: 0.11
Nodes (20): bind_arguments(), boolean_tersimpan_sebagai_integer(), decode_hrana_cell(), decode_local_cell(), integer_besar_tidak_kehilangan_presisi(), kolom_dan_baris_terbaca_sesuai_urutan(), LOCAL_PRAGMAS, LocalTransport (+12 more)

### Community 80 - "operators/page.tsx"
Cohesion: 0.08
Nodes (47): ActiveTab, EDITABLE_PERMISSION_GROUPS, EMPTY_OPERATOR, errorMessage(), FormField(), MasterOperatorPage(), ModalActions(), OperatorFormModal() (+39 more)

### Community 81 - "services/correction.ts"
Cohesion: 0.10
Nodes (37): formatDateTime(), LogRemoval, rebuildAttendanceFromLogs(), RebuildResult, SqlExecutor, aturanShiftDariBaris(), hitungMenitKerjaPadaGarisWaktu(), hitungUlangAbsensiDariJam() (+29 more)

### Community 82 - "MailSettingsCard.tsx"
Cohesion: 0.15
Nodes (27): MailSettingsCard(), getMailConfig(), JsonRecord, MailTestResult, normalizeConfig(), record(), saveMailConfig(), sendTestMail() (+19 more)

### Community 83 - "csp"
Cohesion: 0.06
Nodes (31): debugApplicationIdSuffix, app, security, windows, build, beforeBuildCommand, beforeDevCommand, devUrl (+23 more)

### Community 84 - "erapor.ts"
Cohesion: 0.13
Nodes (29): bacaPemetaan(), DialogErapor(), ekspor(), ubahPemetaan(), namaBerkas(), pemetaanSah(), simpanPemetaan(), getBahanErapor() (+21 more)

### Community 85 - "gateways/grades.ts"
Cohesion: 0.15
Nodes (26): buatIdNilai(), GradeValidationError, jenisSaringan(), jenisTidakDikenal(), jenisUntukSimpan(), saveAssessment(), saveScores(), teksWajib() (+18 more)

### Community 86 - "berkas_sekolah.rs"
Cohesion: 0.11
Nodes (27): ambil_berkas_siswa(), batas_ukuran_dihitung_dari_isi(), BerkasSah, daftar_berkas_siswa(), galat_validasi(), hapus_berkas_pmb(), hapus_berkas_siswa(), id_berkas() (+19 more)

### Community 87 - "TursoConfig"
Cohesion: 0.06
Nodes (26): BUILD_OFFLINE_MAX_AGE_HOURS, BUILD_TURSO_AUTH_TOKEN, BUILD_TURSO_DATABASE_URL, DESKTOP_HTTP_TIMEOUT_SECONDS, parse_bool_setting(), parse_offline_hours(), parse_offline_hours_value(), parse_provider_setting() (+18 more)

### Community 88 - "KasbonWorkspace.tsx"
Cohesion: 0.18
Nodes (23): bacaNominal(), bulanIni(), DialogDetail(), jalankan(), DialogPengajuan(), simpan(), Feedback, Filter (+15 more)

### Community 89 - "wa_sender.rs"
Cohesion: 0.13
Nodes (18): config(), drain(), fonnte_rejection(), int(), keputusan_baris_antrean(), permintaan_per_provider(), provider_request(), ProviderRequest (+10 more)

### Community 90 - "validations/class-attendance.ts"
Cohesion: 0.08
Nodes (41): ClassAttendanceSessionFilter, DEFAULT_ROSTER_STATUS, getAttendanceReconciliation(), SaveClassAttendanceDraft, StudentAttendanceDraftItem, buildPresentWithoutGateScanWarning(), CakupanBel, composeReconciliationMessage() (+33 more)

### Community 91 - "validations/nilai-akhir.ts"
Cohesion: 0.12
Nodes (15): BarisTahunAjaran, BATAS_PENILAIAN_REKAP, BobotJenis, HARI_SEKOLAH_BAWAAN, JENIS_NILAI_BAWAAN, JENIS_WARISAN_BUATAN, JenisBawaan, JenisNilaiDraft (+7 more)

### Community 92 - "attendance_dashboard.rs"
Cohesion: 0.12
Nodes (21): baca_statistik(), dasbor_kosong_tetap_berhasil(), db_error(), GATE_SUMMARY_SUBQUERY, get_attendance_dashboard_metrics(), KelompokPersonil, GuruPtk, Siswa (+13 more)

### Community 93 - "scripts"
Cohesion: 0.07
Nodes (27): scripts, bootstrap:superadmin, build, build:desktop, build:web, check, check:quick, dev (+19 more)

### Community 94 - "database-config.ts"
Cohesion: 0.09
Nodes (23): client, config, email, name, noHp, password, username, noStoreJson() (+15 more)

### Community 95 - "gateways/password-reset-history.ts"
Cohesion: 0.19
Nodes (15): isResetHistoryStatus(), RESET_HISTORY_DEFAULT_LIMIT, RESET_HISTORY_MAX_LIMIT, RESET_HISTORY_STATUS_HINT, RESET_HISTORY_STATUS_TONE, RESET_HISTORY_STATUSES, ResetHistoryEntry, ResetHistoryFilter (+7 more)

### Community 96 - "konten_gambar.rs"
Cohesion: 0.10
Nodes (18): ambil(), GambarTerurai, HAPUS_GAMBAR_YATIM_SQL, id_gambar_konten(), id_gambar_konten_sah(), JENIS_GAMBAR_KONTEN, JPEG, MAKS_BYTE_GAMBAR_KONTEN (+10 more)

### Community 97 - "wa-sender.ts"
Cohesion: 0.21
Nodes (13): buatPermintaanProvider(), PermintaanProvider, readFullWaConfig(), sendViaProvider(), StoredWaConfig, aksiBarisAntrean, DrainResult, drainWaQueue() (+5 more)

### Community 98 - "validate_mutation"
Cohesion: 0.11
Nodes (26): alasan_sah_untuk(), ASET, BarangDraft, BarangInfo, BarangValid, clean(), clean_tempat(), draft() (+18 more)

### Community 99 - "package.json"
Cohesion: 0.08
Nodes (24): engines, bun, node, name, overrides, nanoid, packageManager, private (+16 more)

### Community 100 - "visual-store.ts"
Cohesion: 0.24
Nodes (14): VisualProvider(), OPTIONS, TIER_LABEL, DEGRADE_STEP, persistPreference(), prefersReducedMotion(), readStoredPreference(), resolveTier() (+6 more)

### Community 101 - "invalid"
Cohesion: 0.19
Nodes (23): assert_saldo_cukup(), barang_dilacak(), buat_unit(), cancel_mutation(), canonical_option(), canonical_tempat(), enqueue_mutasi(), insert_mutasi() (+15 more)

### Community 102 - "Value"
Cohesion: 0.17
Nodes (18): apply_snapshot_with_pulse(), apply_table(), apply_tombstones(), attendance_row(), enqueue_employee_snapshot(), entity_key(), guard_key(), is_device_local_setting() (+10 more)

### Community 103 - "operator-admin.ts"
Cohesion: 0.12
Nodes (28): ask(), main(), rl, hashPassword(), assertOperatorContact(), isValidOperatorEmail(), maskPhone(), normalizeOperatorEmail() (+20 more)

### Community 104 - "DeviceProfileCard.tsx"
Cohesion: 0.15
Nodes (21): DeviceProfileCard(), explainTier(), TIER_LABEL, TIER_TONE, VisualState, DeviceProfile, DeviceProfileEntry, NavigatorWithUaData (+13 more)

### Community 105 - "engine.rs"
Cohesion: 0.11
Nodes (8): jp_tanpa_tarif_dihitung_terpisah_dan_tidak_menggagalkan_apa_pun(), sesi(), tarif(), VEKTOR, VEKTOR_CALC, VEKTOR_LEMBUR, VEKTOR_SASARAN, VEKTOR_TANPA_JENJANG_LIBUR

### Community 106 - "dependencies"
Cohesion: 0.09
Nodes (22): dependencies, clsx, jspdf, jspdf-autotable, @libsql/client, motion, next, postcss (+14 more)

### Community 107 - "@playwright/test"
Cohesion: 0.15
Nodes (9): LIMITED_STATE, STORAGE_STATE_DIR, SUPERADMIN_STATE, dotenv, @playwright/test, loginViaForm(), logoutViaApi(), test (+1 more)

### Community 108 - "services/holiday-whitelist.ts"
Cohesion: 0.22
Nodes (17): assertNoDuplicate(), newWhitelistId(), normalizeInput(), rowToEntry(), tambahHolidayWhitelist(), updateHolidayWhitelist(), evaluateHolidayScan(), foldWhitelistText() (+9 more)

### Community 109 - "queue_wali_notification_tx"
Cohesion: 0.17
Nodes (13): compose_wa_message(), notifikasi_wali_dedupe_sekali_saja(), notifikasi_wali_hanya_untuk_siswa(), notifikasi_wali_menghormati_sakelar(), nyalakan(), pemangkasan_hanya_baris_selesai_dan_sudah_terkirim(), purge_expired_notifications(), render_template_sesuai_vektor() (+5 more)

### Community 110 - "bootstrap.ts"
Cohesion: 0.11
Nodes (27): BootstrapPanel(), BootstrapPanelProps, TONE_BADGE, TONE_CARD, TONE_LABEL, LicenseBootstrapField(), BootstrapDraft, BootstrapStatus (+19 more)

### Community 111 - "AttendanceGauge3D.tsx"
Cohesion: 0.18
Nodes (18): @react-three/fiber, three, AttendanceGauge3D(), AttendanceGauge3DProps, CHART_VARS, readChartPalette(), RingSegment(), Scene() (+10 more)

### Community 112 - "notifikasi-wa/page.tsx"
Cohesion: 0.11
Nodes (36): NotifikasiWaPage(), DatabaseBackupCard(), formatSize(), WaQueueEmptyDiagnostic(), WaQueueEmptyDiagnosticProps, WaTemplateDialog(), NAMA_HARI_PENGINGAT, NotifikasiWaCardProps (+28 more)

### Community 113 - "PayrollCalculator"
Cohesion: 0.15
Nodes (5): dasar_negatif_tidak_pernah_mengurangi_tunjangan(), jenis_perhitungan_komponen_dihitung_dari_dasar_masing_masing(), normalize_personnel_role(), PayrollCalculator, upah_dari_menit_membulatkan_titik_tengah_menjauhi_nol()

### Community 114 - "ip-allowlist.ts"
Cohesion: 0.23
Nodes (17): RFC-5952, formatIpAddress(), formatIpv4(), formatIpv6(), ipMatchesAllowlist(), matchesEntry(), MAX_IP_ALLOWLIST_ENTRIES, normalizeIpEntry() (+9 more)

### Community 115 - "grades/delete/route.ts"
Cohesion: 0.24
Nodes (7): POST(), runtime, POST(), runtime, deleteAssessment(), getAssessment(), GradeNotFoundError

### Community 116 - "super"
Cohesion: 0.15
Nodes (11): hari_iso(), HARI_KERJA_SEMUA, JENIS_LIBUR, LiburMassal, MAKS_LIBUR_MASSAL, parse_hari_kerja(), tanggal_valid(), validasi_libur_massal() (+3 more)

### Community 117 - "pmb_bayar.rs"
Cohesion: 0.15
Nodes (12): belum_lunas(), KeadaanPendaftar, konfirmasi_bayar(), METODE_BAYAR_PMB, p(), SQL_KEADAAN_BAYAR_PMB, SQL_MEMAKAN_KUOTA_PMB, STATUS_TUTUP (+4 more)

### Community 118 - "compilerOptions"
Cohesion: 0.11
Nodes (18): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+10 more)

### Community 119 - "Value"
Cohesion: 0.18
Nodes (17): baca_atribut(), cloud_column_values(), cloud_item_values(), cloud_keeps_decimal_flag_when_payload_omits_it(), cloud_mutation_values(), cloud_unit_values(), is_valid_date(), list_recipients() (+9 more)

### Community 120 - "save_item"
Cohesion: 0.15
Nodes (18): barang_json(), delete_column(), delete_column_purges_values_and_cannot_be_revived(), enqueue_kolom(), format_kode_barang(), is_angka_kanonik(), is_id_kolom(), kode_dipakai() (+10 more)

### Community 121 - "ekspor.ts"
Cohesion: 0.14
Nodes (26): bacaPilihan(), DialogEkspor(), simpanPilihan(), daftarKolomEkspor(), eksporInventaris(), eksporKartuStok(), eksporPengadaan(), isiKolom() (+18 more)

### Community 122 - "attendance-photos/query/route.ts"
Cohesion: 0.24
Nodes (17): PhotoQueryBody, POST(), runtime, ATTENDANCE_PHOTO_MAX_LIMIT, AttendancePhotoEntry, AttendancePhotoFilter, AttendancePhotoImage, attendancePhotoLimit() (+9 more)

### Community 123 - "DecisionReason"
Cohesion: 0.12
Nodes (17): rejected_decision_message(), DecisionReason, AlreadyCheckedOut, CheckoutTooLate, CheckoutWithoutEntry, EarlyCheckout, EarlyEntry, EntryWindowClosed (+9 more)

### Community 124 - "TiltCard.tsx"
Cohesion: 0.13
Nodes (18): clsx, motion, tailwind-merge, AnimatedCounter(), AnimatedCounterProps, numberFormat, render(), AuroraBackground() (+10 more)

### Community 125 - "gateways/license.ts"
Cohesion: 0.19
Nodes (19): LicenseActivationPanel(), Props, TITLES, Props, describeDaysLeft(), LicenseCard(), STATE_LABEL, getLicenseStatus() (+11 more)

### Community 126 - "types/pmb.ts"
Cohesion: 0.14
Nodes (21): belumLunas(), KEADAAN_BAYAR_PMB, KeadaanBayarPmb, KeadaanPendaftarPmb, METODE_BAYAR_PMB, MetodeBayarPmb, rupiahPmb(), SQL_KEADAAN_BAYAR_PMB (+13 more)

### Community 127 - "PageContentManager.tsx"
Cohesion: 0.09
Nodes (35): CollectionRepeater(), CollectionRepeaterProps, FieldKoleksi, nilaiTeks(), GambarKontenInput(), siapkanFotoKonten(), usePratinjauGambar(), HeroImageUploader() (+27 more)

### Community 129 - "gateways/password-reset.ts"
Cohesion: 0.18
Nodes (21): LupaPasswordPage(), Step, STEP_LABELS, StepIndicator(), PageShell(), ResetPasswordForm(), ResetPasswordPage(), asChallenges() (+13 more)

### Community 130 - "biome.json"
Cohesion: 0.15
Nodes (12): source, assist, actions, next, react, extends, linter, domains (+4 more)

### Community 131 - "devDependencies"
Cohesion: 0.15
Nodes (13): devDependencies, babel-plugin-react-compiler, @biomejs/biome, dotenv, @playwright/test, @tauri-apps/cli, @types/bun, @types/node (+5 more)

### Community 132 - "migrate-old-db.ts"
Cohesion: 0.18
Nodes (10): migrationEventId(), migrationFailures, nowEpoch, outboxStmt, sha256(), sourceDb, sourceDbPath, tablesToMigrate (+2 more)

### Community 133 - "bel-perangkat.ts"
Cohesion: 0.17
Nodes (21): BelPerangkatPanel(), BelPerangkatPanelProps, bacaConfigBel(), bacaMp3(), BEL_BERUBAH_EVENT, bukaDb(), bunyikanBel(), ConfigBel (+13 more)

### Community 134 - "impor-dapodik.ts"
Cohesion: 0.15
Nodes (18): TombolImporDapodikSiswa(), baca(), bersihkan(), cocokkanSiswaDapodik(), galatIsian(), KELOMPOK_ORANG_TUA, KOLOM_ISIAN, KUNCI_ATAS (+10 more)

### Community 135 - "database-promotion.ts"
Cohesion: 0.27
Nodes (9): assertPromotionOrder(), detectUniqueCollisions(), planIdRemap(), PROMOTION_EXCLUDED_TABLES, PROMOTION_PLAN, PromotionTable, Row, rowKey() (+1 more)

### Community 136 - "riwayat-reset-password/page.tsx"
Cohesion: 0.24
Nodes (18): DetailRow(), formatScore(), formatTimestamp(), HistoryCard(), RiwayatResetPasswordPage(), StatusFilter, SummaryTile(), approvePasswordReset() (+10 more)

### Community 137 - "payroll_seed.rs"
Cohesion: 0.33
Nodes (8): default_rate_ids(), legacy_rate_ids(), seed_statements(), sql_values(), TabelSeed, tarif_bawaan(), tarif_bawaan_lengkap_dan_tidak_memuat_id_lama(), TarifBawaan

### Community 138 - "run-tests.ts"
Cohesion: 0.20
Nodes (6): result, collectTests(), runTest(), tests, worker(), workers

### Community 139 - "face-template/route.ts"
Cohesion: 0.29
Nodes (9): DELETE(), POST(), PUT(), runtime, SAVE_KEYS, SaveBody, deleteFaceTemplate(), listFaceTemplates() (+1 more)

### Community 140 - "resolve_bootstrap_turso_config"
Cohesion: 0.39
Nodes (6): desktop_check_bootstrap_database(), desktop_link_bootstrap_database(), ensure_bootstrap_window_open(), mode_lokal_tidak_menuntut_alamat_saat_provisioning(), provider_remote_tetap_menuntut_alamat(), resolve_bootstrap_turso_config()

### Community 141 - "DapodikSiswa.tsx"
Cohesion: 0.16
Nodes (18): DaftarRincian(), dataDariDraf(), Draf, drafDariBaris(), Isian, KELOMPOK, KUNCI_ATAS, LABEL_ISIAN (+10 more)

### Community 142 - "detail/route.ts"
Cohesion: 0.40
Nodes (5): bodySchema, POST(), runtime, loanDetail(), text()

### Community 143 - "types/accounting.ts"
Cohesion: 0.18
Nodes (17): DraftAkun, HeaderTulis, KelompokAkun, SaldoNormal, SumberJurnal, AkunItem, BarisLaporanAkun, BukuBesar (+9 more)

### Community 144 - "AttendanceGaugeGate.tsx"
Cohesion: 0.31
Nodes (8): AttendanceGauge3D, AttendanceGaugeGate(), AttendanceGaugeProps, SvgDonutFallback(), LoginScene, LoginSceneGate(), LoginSceneGateProps, isWebGLAvailable()

### Community 145 - "PayrollStatus"
Cohesion: 0.22
Nodes (7): PayrollStatus, Approved, Draft, Paid, Rejected, Reviewed, Submitted

### Community 146 - "SPPG App - Tech Stack & Architecture Rules"
Cohesion: 0.22
Nodes (8): 1. Unified Stack Overview, 2. Tri-Platform Database Schema Synchronization (Zero-Drift Policy), 3. Codebase Exploration & Anti-Duplication Rule (Single Source of Truth), 4. Ironclad Backend Logic & Sync Security, 5. Gateway Pattern & Runtime Abstraction, 6. Tauri v2 Desktop & Mobile Rust Backend Rules, 7. Android APK & Mobile Readiness, SPPG App - Tech Stack & Architecture Rules

### Community 147 - "SPPG Attendance Fullstack Development Skill & Knowledge Base"
Cohesion: 0.22
Nodes (8): 1. Tri-Platform Database Schema Synchronization (Zero-Drift Policy), 2. Codebase Exploration, Anti-Duplication, & Architecture Preservation, 4. UI/UX Engineering & CSS Sticky Table Precision, 5. Troubleshooting & Problem-Solving Guide, 6. Quality Gate Zero-Error Checklist, A. Rust / Tauri Desktop Gotchas, B. Next.js, Tauri v2 Static Export & Bun Test Gotchas, SPPG Attendance Fullstack Development Skill & Knowledge Base

### Community 148 - "build.rs"
Cohesion: 0.33
Nodes (6): assert_offline_hours_present_on_release(), DESKTOP_COMMANDS, expose_build_date(), expose_build_value(), local_build_values(), main()

### Community 149 - "employee-identity.ts"
Cohesion: 0.27
Nodes (9): entriesOf(), getRiwayatIdentitasKaryawan(), JsonRecord, listRiwayatIdentitasKaryawan(), EMPLOYEE_IDENTITY_FIELDS, LABEL_IDENTITAS_KARYAWAN, normalisasiRiwayatIdentitas(), parseRingkasan() (+1 more)

### Community 150 - "attendance_ledger.rs"
Cohesion: 0.26
Nodes (12): delete_frozen_ledger(), float(), freeze_attendance_ledger(), get_frozen_ledger(), get_ledger_preview(), integer(), new_ledger_id(), _optional_text() (+4 more)

### Community 151 - "test-data.ts"
Cohesion: 0.25
Nodes (5): API_TIMEOUT, JENIS_KELAMIN_VALID, PROTECTED_ROUTES, STATUS_GURU_VALID, STATUS_SISWA_VALID

### Community 152 - "Zero-Error & Zero-Warning Code Standards"
Cohesion: 0.29
Nodes (6): 1. Quality Gate Command, 2. Biome Linter & Formatter Precision Rules, 3. TypeScript Strictness & Client/Server Boundaries, 4. Excel & Spreadsheet Processing Standard, 5. Rust & Tauri v2 Standards, Zero-Error & Zero-Warning Code Standards

### Community 153 - "next.config.ts"
Cohesion: 0.29
Nodes (6): buildDateWib, humanBrowserEntry, nextConfig, SECURITY_HEADERS, zxingBrowserEntry, zxingLibraryEntry

### Community 154 - "Absensi SPPG"
Cohesion: 0.29
Nodes (6): Absensi SPPG, Development, Environment Desktop per pelanggan, Environment Web/Vercel, Quality gate, Target build

### Community 155 - "jp/route.ts"
Cohesion: 0.52
Nodes (6): POST(), PUT(), runtime, unitDari(), readJpSettings(), jpUnitKey()

### Community 156 - "license.test.ts"
Cohesion: 0.38
Nodes (6): BASE, reject(), sign(), TEST_KEY, UJI, withChanges()

### Community 157 - "default.json"
Cohesion: 0.29
Nodes (6): description, identifier, local, permissions, $schema, windows

### Community 159 - "attendance-photos/route.ts"
Cohesion: 0.47
Nodes (5): DELETE(), PhotoDeleteBody, runtime, deleteAttendancePhoto(), purgeAttendancePhotos()

### Community 160 - "database-retry.ts"
Cohesion: 0.60
Nodes (4): errorChain(), isTransientDatabaseError(), TRANSIENT_DATABASE_ERROR_CODES, withTransientDatabaseRetry()

### Community 161 - "assert_offline_login_allowed"
Cohesion: 0.53
Nodes (5): akun_ber_2fa_ditolak_pada_jalur_offline(), assert_offline_login_allowed(), kode_penolakan_offline_tidak_bentrok_dengan_kode_2fa_online(), operator(), pesan_offline_tidak_memuat_frasa_pemicu_layar_kode()

### Community 162 - "Value"
Cohesion: 0.47
Nodes (5): delete_template(), invalid(), list_templates(), save_template(), template_json()

### Community 163 - "PengaturanNilai.tsx"
Cohesion: 0.25
Nodes (16): DialogJenis(), jalankan(), NAMA_HARI, PanelBobot(), simpan(), PanelHariSekolah(), simpan(), PengaturanNilai() (+8 more)

### Community 164 - "json"
Cohesion: 0.26
Nodes (10): delete_teaching_journal(), get_teaching_journal(), list_teaching_journals(), new_journal_id(), optional_text(), save_teaching_journal(), setup_test_state(), sqlite_now() (+2 more)

### Community 165 - "whitelist/route.ts"
Cohesion: 0.19
Nodes (13): DELETE(), parseDraft(), parseId(), PATCH(), POST(), runtime, WhitelistMutationBody, POST() (+5 more)

### Community 166 - "save-portal/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, savePortal()

### Community 167 - "shift/page.tsx"
Cohesion: 0.29
Nodes (12): formatMenitJam(), hitungJamKerjaNormalOtomatis(), parseTimeToMinutes(), pratinjauJendelaMasuk(), ShiftPage(), PilihHariKerja(), hapusShift(), ShiftDraft (+4 more)

### Community 168 - "siapkan-berkas.ts"
Cohesion: 0.21
Nodes (14): KelolaBerkas(), buang(), jalankan(), unggah(), optimizeImageDataUrl(), bacaDataUrl(), HasilSiapkanBerkas, isiBase64() (+6 more)

### Community 170 - "validations/siswa-dapodik.ts"
Cohesion: 0.24
Nodes (8): saveSiswaDapodik(), BarisDapodikSiswa, MAKS_ID_BACA_DAPODIK, PESAN_SISWA_BELUM_DI_CLOUD, SimpanDapodikSiswa, SQL_KOSONGKAN_DAPODIK_SISWA, SQL_SIMPAN_DAPODIK_SISWA, validasiSimpanDapodikSiswa()

### Community 171 - "RowAction"
Cohesion: 0.40
Nodes (5): row_action(), RowAction, CancelDisabled, CancelDuplicate, Send

### Community 172 - "build"
Cohesion: 0.40
Nodes (4): build, beforeDevCommand, devUrl, $schema

### Community 173 - "deserialize"
Cohesion: 0.29
Nodes (8): DesktopLoginResult, DesktopRuntimeStatus, DesktopSession, OfflineCredential, OperatorUser, SessionMode, Offline, Online

### Community 174 - "setup/page.tsx"
Cohesion: 0.31
Nodes (9): SetupPage(), Shell(), View, DATABASE_NOT_CONFIGURED_DESCRIPTION, DATABASE_NOT_CONFIGURED_TITLE, DatabaseNotConfiguredNotice(), Props, createWebSuperadmin() (+1 more)

### Community 185 - "parse_wa_switches"
Cohesion: 0.25
Nodes (11): cerminan_lokal_langsung_terbaca_scanner(), clamp_ambang_alfa_days(), clamp_ambang_alfa_limit(), clamp_pengingat_hari_lewat(), clamp_pengingat_hari_sebelum(), mirror_wa_switches_local(), parse_wa_switches(), sakelar_wa_bawaannya_mati_semua() (+3 more)

### Community 186 - "images/query/route.ts"
Cohesion: 0.24
Nodes (7): bodySchema, POST(), runtime, bodySchema, POST(), runtime, ContentValidationError

### Community 187 - "recipients/route.ts"
Cohesion: 0.24
Nodes (8): bodySchema, POST(), runtime, bodySchema, POST(), runtime, listRecipients(), formData()

### Community 188 - ".as_str"
Cohesion: 0.29
Nodes (4): DatabaseConfigView, parse_liveness_report(), snapshot_window_column(), tarik_inkremental_tabel_append_only()

### Community 189 - "DataDapodikPmb.tsx"
Cohesion: 0.33
Nodes (8): Baris, DataDapodikDetail(), Kelompok(), barisEksporDapodik(), hpLokal(), teksSel(), uraiDataDapodik(), PmbRegistrantFilter

### Community 190 - "Value"
Cohesion: 0.28
Nodes (8): cancel_wa_notification(), cancel_wa_notification_tx(), flag(), get_wa_templates(), list_wa_notifications(), queue_wa_notification(), save_wa_templates(), test_wa_notification_lifecycle()

### Community 191 - "createBrandingMirror"
Cohesion: 0.50
Nodes (8): createBrandingMirror(), emit(), getSnapshot(), readCache(), refreshFromRemote(), setSnapshot(), subscribe(), writeCache()

### Community 192 - "queue_wali_notification_tx"
Cohesion: 0.39
Nodes (7): is_valid_phone(), new_wa_notification_id(), normalize_phone_canonical(), queue_wa_notification_tx(), queue_wali_notification_tx(), wa_notify_enabled(), wa_notify_setting_key()

### Community 193 - "grades/query/route.ts"
Cohesion: 0.40
Nodes (5): bodySchema, opsional, POST(), runtime, listAssessments()

### Community 194 - "wali-credentials/route.ts"
Cohesion: 0.47
Nodes (5): daftarKredensial(), pernyataanTerbitkan(), POST(), runtime, StatusKredensial

### Community 195 - "company-profile/route.ts"
Cohesion: 0.47
Nodes (4): prepare(), PUT(), runtime, CompanyProfileInput

### Community 196 - ".save_article"
Cohesion: 0.40
Nodes (4): is_valid_cover_image_data_uri(), new_pmb_id(), slugify(), teks_wajib()

### Community 197 - "compose_from_stored"
Cohesion: 0.40
Nodes (6): compose_from_stored(), default_wa_template(), render_wa_template(), validasi_template_sesuai_vektor(), validate_wa_template(), wa_template_placeholders()

### Community 198 - "loans/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, listLoans()

### Community 199 - "opname-history/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, opnameHistory()

### Community 200 - "undefer/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, undeferLoan()

### Community 201 - "uks/delete/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, deleteVisit()

### Community 202 - "get_jp_settings"
Cohesion: 0.50
Nodes (4): assert_unit_exists(), get_jp_settings(), jp_unit_key(), save_jp_settings()

## Knowledge Gaps
- **81 isolated node(s):** `../biome.json`, `@tailwindcss/postcss`, `postcss`, `tailwindcss`, `@biomejs/biome` (+76 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 2024 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **13 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next` connect `toApiErrorResponse` to `gateways/password-reset.ts`, `isDesktopRuntime`, `Modal`, `ApiRequestError`, `sync-status.ts`, `riwayat-reset-password/page.tsx`, `siswa/page.tsx`, `ref_bun_test`, `face-template/route.ts`, `api-response.ts`, `presensi-kelas/page.tsx`, `detail/route.ts`, `AttendanceGaugeGate.tsx`, `next`, `next.config.ts`, `jp/route.ts`, `authorize.ts`, `attendance-photos/route.ts`, `auth/password-reset.ts`, `whitelist/route.ts`, `save-portal/route.ts`, `shift/page.tsx`, `scanner/page.tsx`, `desktop-session-store.ts`, `setup/page.tsx`, `Icon`, `two-factor/route.ts`, `request-security.ts`, `images/query/route.ts`, `recipients/route.ts`, `shifts/route.ts`, `kickDesktopSync`, `grades/query/route.ts`, `wali-credentials/route.ts`, `company-profile/route.ts`, `loans/route.ts`, `opname-history/route.ts`, `undefer/route.ts`, `uks/delete/route.ts`, `services/counseling.ts`, `useAuth`, `operators/page.tsx`, `database-config.ts`, `package.json`, `notifikasi-wa/page.tsx`, `grades/delete/route.ts`, `attendance-photos/query/route.ts`?**
  _High betweenness centrality (0.075) - this node is a cross-community bridge._
- **What connects `../biome.json`, `@tailwindcss/postcss`, `postcss` to the rest of the system?**
  _81 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `toApiErrorResponse` be split into smaller, more focused modules?**
  _Cohesion score 0.019999748114003603 - nodes in this community are weakly interconnected._
- **Why does `CommandError` connect `CommandError` to `billing.rs`, `resolve_bootstrap_turso_config`, `accounting.rs`, `academic.rs`, `turso.rs`, `TursoClient`, `operational.rs`, `attendance_ledger.rs`, `nilai_akhir.rs`, `payroll/commands.rs`, `loan.rs`, `.baca_keadaan_bayar_pmb`, `assert_offline_login_allowed`, `Value`, `sync.rs`, `json`, `scanner.rs`, `class_attendance.rs`, `tutup_buku.rs`, `inventory.rs`, `administration.rs`, `uks.rs`, `grades.rs`, `deserialize`, `rapel.rs`, `baca_slip`, `wa_notification.rs`, `.fmt`, `parse_wa_switches`, `.ensure_schema`, `license.rs`, `siswa_dapodik.rs`, `.as_str`, `Value`, `face_match.rs`, `queue_wali_notification_tx`, `secrets.rs`, `storage.rs`, `.save_article`, `get_jp_settings`, `fixture`, `setup_state`, `portability.rs`, `sql_backend.rs`, `berkas_sekolah.rs`, `TursoConfig`, `wa_sender.rs`, `attendance_dashboard.rs`, `konten_gambar.rs`, `invalid`, `Value`, `queue_wali_notification_tx`, `Value`, `save_item`?**
  _High betweenness centrality (0.062) - this node is a cross-community bridge._
- **Should `CommandError` be split into smaller, more focused modules?**
  _Cohesion score 0.027659574468085105 - nodes in this community are weakly interconnected._
- **Why does `ensureServerDatabaseInitialized()` connect `ApiRequestError` to `toApiErrorResponse`, `face-template/route.ts`, `api-response.ts`, `detail/route.ts`, `next`, `jp/route.ts`, `authorize.ts`, `attendance-photos/route.ts`, `auth/password-reset.ts`, `whitelist/route.ts`, `save-portal/route.ts`, `db-migrations.ts`, `two-factor/route.ts`, `attendance-processor.ts`, `hari-kerja.ts`, `services/tutup-buku.ts`, `request-security.ts`, `images/query/route.ts`, `recipients/route.ts`, `shifts/route.ts`, `grades/query/route.ts`, `wali-credentials/route.ts`, `company-profile/route.ts`, `loans/route.ts`, `opname-history/route.ts`, `undefer/route.ts`, `uks/delete/route.ts`, `services/counseling.ts`, `face-match.ts`, `services/correction.ts`, `validations/class-attendance.ts`, `services/holiday-whitelist.ts`, `grades/delete/route.ts`, `attendance-photos/query/route.ts`?**
  _High betweenness centrality (0.035) - this node is a cross-community bridge._
- **Should `isDesktopRuntime` be split into smaller, more focused modules?**
  _Cohesion score 0.03304638928742228 - nodes in this community are weakly interconnected._