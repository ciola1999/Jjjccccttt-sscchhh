# Graph Report - web-desktop  (2026-10-23)

## Corpus Check
- 858 files · ~917,159 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 352 file(s) not represented in the graph (top: .toml 341, (none) 5, .ico 2)

## Summary
- 8309 nodes · 31175 edges · 185 communities (171 shown, 14 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 167 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `9daea321`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- toApiErrorResponse
- CommandError
- isDesktopRuntime
- react
- ApiRequestError
- login/page.tsx
- Icon
- billing.rs
- validations/inventory.ts
- siswa/page.tsx
- ref_bun_test
- pesanGalat
- ensureServerDatabaseInitialized
- presensi-kelas/page.tsx
- services/billing.ts
- accounting.rs
- academic.rs
- turso.rs
- TursoClient
- DapodikSiswa.tsx
- services/accounting.ts
- operational.rs
- InventarisWorkspace.tsx
- pmb-admin.ts
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
- dashboard/page.tsx
- db-migrations.ts
- two-factor/route.ts
- attendance-processor.ts
- server/license.ts
- services/loan.ts
- hari-kerja.ts
- services/tutup-buku.ts
- request-security.ts
- login/route.ts
- .ensure_schema
- license.rs
- siswa_dapodik.rs
- shifts/route.ts
- content-admin.ts
- face_match.rs
- akademik/page.tsx
- time-policy.ts
- secrets.rs
- storage.rs
- services/payroll-rapel.ts
- saveFileWithPicker
- face-match.ts
- services/nilai-akhir.ts
- api-response.ts
- services/counseling.ts
- id-cards/page.tsx
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
- TutupBukuPanel.tsx
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
- LabelQr.tsx
- DeviceProfileCard.tsx
- engine.rs
- dependencies
- @playwright/test
- services/holiday-whitelist.ts
- queue_wali_notification_tx
- config.rs
- AttendanceGauge3D.tsx
- isMobileRuntime
- PayrollCalculator
- ip-allowlist.ts
- services/grades.ts
- super
- pmb_bayar.rs
- compilerOptions
- Value
- save_item
- enforce_any
- attendance-photos/query/route.ts
- DecisionReason
- bimbingan-konseling/page.tsx
- .authenticate_operator
- backups/route.ts
- landing-cms-fields.ts
- AudioSynthesizer
- Evaluation
- biome.json
- devDependencies
- migrate-old-db.ts
- templates/route.ts
- services/attendance-audit.ts
- database-promotion.ts
- with
- payroll_seed.rs
- run-tests.ts
- face-template/route.ts
- resolve_bootstrap_turso_config
- rekapPdf.ts
- detail/route.ts
- RekapNilai.tsx
- AttendanceGaugeGate.tsx
- PayrollStatus
- SPPG App - Tech Stack & Architecture Rules
- SPPG Attendance Fullstack Development Skill & Knowledge Base
- build.rs
- employee-identity.ts
- validate_payload
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
- LicenseState
- backfill/route.ts
- delete-rate/route.ts
- save-portal/route.ts
- employees/query/route.ts
- teachers/query/route.ts
- security-mutation.ts
- import_payload
- RowAction
- build
- device_name
- test_key
- baca_slip
- android-bridge.d.ts
- postcss.config.mjs
- sumber/README.md
- manajemen_sekolah_desktop

## God Nodes (most connected - your core abstractions)
1. `CommandError` - 987 edges
2. `DesktopState` - 698 edges
3. `ensureServerDatabaseInitialized()` - 637 edges
4. `toApiErrorResponse()` - 505 edges
5. `noStoreJson()` - 504 edges
6. `assertSameOriginMutation()` - 480 edges
7. `requireWebPermission()` - 474 edges
8. `isDesktopRuntime()` - 389 edges
9. `getServerDatabase()` - 369 edges
10. `readJsonBody()` - 316 edges

## Surprising Connections (you probably didn't know these)
- `5. Gateway Pattern & Runtime Abstraction` --references--> `isDesktopRuntime()`  [INFERRED]
  .agents/rules/tech-stack-architecture.md → src/lib/runtime/app-runtime.ts
- `3. Ironclad Backend Logic, Data Security & Sync Integrity` --references--> `AppShell()`  [INFERRED]
  .agents/skills/sppg-fullstack/SKILL.md → src/components/AppShell.tsx
- `B. Next.js, Tauri v2 Static Export & Bun Test Gotchas` --references--> `AutoAlfaRunner()`  [INFERRED]
  .agents/skills/sppg-fullstack/SKILL.md → src/components/AutoAlfaRunner.tsx
- `Manajemen Sekolah - Core Engineering Rules` --references--> `Modal()`  [INFERRED]
  AGENTS.md → src/components/ui/Modal.tsx
- `Manajemen Sekolah - Core Engineering Rules` --references--> `isDesktopRuntime()`  [INFERRED]
  AGENTS.md → src/lib/runtime/app-runtime.ts

## Import Cycles
- 1-file cycle: `src-tauri/src/desktop/config.rs -> src-tauri/src/desktop/config.rs`
- 1-file cycle: `src-tauri/src/desktop/storage.rs -> src-tauri/src/desktop/storage.rs`
- 1-file cycle: `src-tauri/src/desktop/sync.rs -> src-tauri/src/desktop/sync.rs`
- 1-file cycle: `src-tauri/src/desktop/administration.rs -> src-tauri/src/desktop/administration.rs`
- 1-file cycle: `src-tauri/src/desktop/commands.rs -> src-tauri/src/desktop/commands.rs`
- 1-file cycle: `src-tauri/src/desktop/class_attendance.rs -> src-tauri/src/desktop/class_attendance.rs`
- 1-file cycle: `src-tauri/src/desktop/operational.rs -> src-tauri/src/desktop/operational.rs`
- 1-file cycle: `src-tauri/src/desktop/secrets.rs -> src-tauri/src/desktop/secrets.rs`
- 1-file cycle: `src-tauri/src/desktop/payroll/commands.rs -> src-tauri/src/desktop/payroll/commands.rs`
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

## Communities (185 total, 14 thin omitted)

### Community 0 - "toApiErrorResponse"
Cohesion: 0.02
Nodes (330): zod, POST(), runtime, bodySchema, POST(), runtime, POST(), runtime (+322 more)

### Community 1 - "CommandError"
Cohesion: 0.03
Nodes (348): cancel_backup(), delete_attendance(), delete_backup(), selaraskan_status_backup(), assert_password_saat_ini(), baris(), desktop_accounting_accounts(), desktop_accounting_close() (+340 more)

### Community 2 - "isDesktopRuntime"
Cohesion: 0.03
Nodes (220): 3. Ironclad Backend Logic, Data Security & Sync Integrity, NilaiPage(), buatPenilaian(), bukaDetail(), hapus(), simpanSemuaNilai(), GELOMBANG_KOSONG, PmbPage() (+212 more)

### Community 3 - "react"
Cohesion: 0.05
Nodes (156): react, react-dom, AuditAbsensiPage(), FILTER_OPTIONS, FilterKeparahan, formatTanggalPanjang(), KEPARAHAN_LABEL, KEPARAHAN_TONE (+148 more)

### Community 4 - "ApiRequestError"
Cohesion: 0.03
Nodes (121): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+113 more)

### Community 5 - "login/page.tsx"
Cohesion: 0.03
Nodes (139): LoginPage(), getLocalGreeting(), Home(), RecentScanItem, SetupPage(), Shell(), View, AppSidebar() (+131 more)

### Community 6 - "Icon"
Cohesion: 0.03
Nodes (137): RFC-1918, zustand, ALLOWED_LOGO_TYPES, FeedbackMessage, SettingsPage(), _SYNC_TABLE_LABELS, JurusanPanel(), JurusanPanelProps (+129 more)

### Community 7 - "billing.rs"
Cohesion: 0.03
Nodes (151): account(), AKUN_PIUTANG_SISWA, AKUN_TITIPAN_WALI, alokasi_pembayaran(), antre_pengingat(), aturan_pembayaran(), baris_jurnal_pembayaran(), BarisPenerimaan (+143 more)

### Community 8 - "validations/inventory.ts"
Cohesion: 0.03
Nodes (155): bacaImporBarang(), FormAwalanKode(), barangDilacak(), buatUnit(), cancelMutation(), canonicalTempat(), deleteColumn(), documentInventaris() (+147 more)

### Community 9 - "siswa/page.tsx"
Cohesion: 0.05
Nodes (121): GuruPage(), KaryawanPage(), SiswaPage(), BATAS_IMPORT_MASSAL, BATAS_KOREKSI_MASSAL, HasilBerurutan, jalankanBerurutan(), jenisPersonil (+113 more)

### Community 10 - "ref_bun_test"
Cohesion: 0.04
Nodes (46): @libsql/client, MODELS, source, target, databasePath, workDir, DRAFT, DATABASE_KEYS (+38 more)

### Community 11 - "pesanGalat"
Cohesion: 0.05
Nodes (111): pesanGalat(), buatKuitansiPdf(), cetakKuitansi(), esc(), keteranganMetode(), namaAlokasi(), tanggalPanjang(), teksKuitansiWa() (+103 more)

### Community 12 - "ensureServerDatabaseInitialized"
Cohesion: 0.03
Nodes (89): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+81 more)

### Community 13 - "presensi-kelas/page.tsx"
Cohesion: 0.04
Nodes (102): PresensiKelasPage(), TabKey, HARI, JadwalDraft, JadwalPanel(), JadwalPanelProps, BelPerangkatPanel(), BelPerangkatPanelProps (+94 more)

### Community 14 - "services/billing.ts"
Cohesion: 0.04
Nodes (108): assertAkunBayar(), nomorUrutBerikutnya(), account(), batalPembayaranTx(), Calon, cancel(), cancelPayment(), catatPembayaranTx() (+100 more)

### Community 15 - "accounting.rs"
Cohesion: 0.05
Nodes (91): akun_bawaan(), akun_json(), akun_nonaktif_dan_kode_ganda_ditolak(), AkunBawaan, AkunDraft, AkunLama, AkunSaldo, AkunValid (+83 more)

### Community 16 - "academic.rs"
Cohesion: 0.05
Nodes (90): assert_unique_value(), assert_unit_exists(), baca_wali_kredensial(), backfill_missing_id_cards(), bulk_issue_wali_passwords(), cache_personnel_photo_local(), chosen_shift(), CLASS_USAGE (+82 more)

### Community 17 - "turso.rs"
Cohesion: 0.03
Nodes (64): ACADEMIC_UNIQUE_RELAXATIONS, ADMIN_DEFAULT_EXCLUDED_PERMISSIONS, assert_attendance_precondition(), assert_operator_deletable(), attendance_session_of(), AttendanceGuardRow, BASE32_ALPHABET, base32_decoding_forgives_human_typing() (+56 more)

### Community 18 - "TursoClient"
Cohesion: 0.08
Nodes (5): MailFailure, reset_error(), TursoClient, .RECOVERY_CODE_COUNT, validate_new_password()

### Community 19 - "DapodikSiswa.tsx"
Cohesion: 0.04
Nodes (78): DaftarRincian(), dataDariDraf(), Draf, drafDariBaris(), Isian, KELOMPOK, KUNCI_ATAS, LABEL_ISIAN (+70 more)

### Community 20 - "services/accounting.ts"
Cohesion: 0.05
Nodes (87): DraftAkun, assertAkunAktif(), assertRentang(), balikJurnalTx(), Executor, HeaderTulis, ledger(), listJournals() (+79 more)

### Community 21 - "operational.rs"
Cohesion: 0.06
Nodes (80): assert_employee_identity_free(), assert_whitelist_unique(), base_revision(), copy_to_public_dir(), create_employee(), create_holiday(), create_holiday_whitelist(), create_holidays_bulk() (+72 more)

### Community 22 - "InventarisWorkspace.tsx"
Cohesion: 0.06
Nodes (82): bacaPilihan(), DialogEkspor(), simpanPilihan(), daftarKolomEkspor(), eksporInventaris(), eksporKartuStok(), eksporPengadaan(), isiKolom() (+74 more)

### Community 23 - "pmb-admin.ts"
Cohesion: 0.05
Nodes (73): KelolaBerkas(), buang(), jalankan(), unggah(), LABEL_METODE, bacaDataUrl(), HasilSiapkanBerkas, isiBase64() (+65 more)

### Community 24 - "next"
Cohesion: 0.04
Nodes (62): next, POST(), runtime, POST(), runtime, POST(), runtime, POST() (+54 more)

### Community 25 - "services/wa-notification.ts"
Cohesion: 0.07
Nodes (75): CONTOH, jenisShift(), menitGenerateAlfa(), selisihHariKalender(), isValidOperatorPhone(), normalizeOperatorPhone(), generateAlfaHarian(), RingkasanAlfa (+67 more)

### Community 26 - "nilai_akhir.rs"
Cohesion: 0.06
Nodes (67): bahan_erapor_dari_rekap_n2(), BarisTahunAjaran, bobot_kehadiran(), bobot_sah(), BobotJenis, bulat_akhir(), cloud_grade_type_values(), CLOUD_UPSERT_GRADE_TYPE_SQL (+59 more)

### Community 27 - "payroll/commands.rs"
Cohesion: 0.06
Nodes (61): APPLIES_TO_ALL, APPLIES_TO_GROUP_PREFIXES, bpjs_rule_id(), desktop_create_payroll_run(), desktop_delete_bpjs_rule(), desktop_delete_jp_rate(), desktop_delete_overtime_rule(), desktop_delete_payroll_component() (+53 more)

### Community 28 - "authorize.ts"
Cohesion: 0.05
Nodes (58): bodySchema, POST(), runtime, bodySchema, POST(), runtime, bodySchema, POST() (+50 more)

### Community 29 - "face-liveness.ts"
Cohesion: 0.06
Nodes (66): LupaPasswordPage(), Step, STEP_LABELS, StepIndicator(), PageShell(), ResetPasswordForm(), ResetPasswordPage(), LivenessCapture() (+58 more)

### Community 30 - "loan.rs"
Cohesion: 0.06
Nodes (61): aktif(), AKUN_BEBAN_BPJS, AKUN_BEBAN_GAJI, AKUN_KAS, AKUN_PIUTANG_KARYAWAN, AKUN_POTONGAN_GAJI, AKUN_UTANG_BPJS, AKUN_UTANG_PPH21 (+53 more)

### Community 31 - "KeuanganWorkspace.tsx"
Cohesion: 0.06
Nodes (64): jspdf, jspdf-autotable, hariIniWib(), akunBaris(), BarisTabel, buatLebarPdf(), buatTabelPdf(), BULAN_PENDEK (+56 more)

### Community 32 - "id-card-renderer.ts"
Cohesion: 0.07
Nodes (64): BuilderPanel(), BuilderPanelProps, LayoutPanel(), LayoutPanelProps, buildCustomLayoutCss(), buildCustomPrintHtml(), bungkusTeks(), DEFAULT_ID_CARD_ELEMENTS (+56 more)

### Community 33 - "tutup_buku.rs"
Cohesion: 0.06
Nodes (59): ALASAN_PEMBERITAHUAN_MATI, ALASAN_SINKRON_BASI, antre_pemberitahuan(), assert_periode_terbuka(), baca_tutup(), banding_saldo(), baris_json(), batas_tutup() (+51 more)

### Community 34 - "sync.rs"
Cohesion: 0.08
Nodes (59): APPEND_ONLY_TABLES, APPEND_PULL_LIMIT, apply_push_results(), apply_snapshot(), apply_snapshot_self_heals_a_stale_local_schema_missing_a_snapshot_table(), assert_cloud_schema_compatible(), CANONICAL_SYNC_ROUTES, clear_failed() (+51 more)

### Community 35 - "auth/password-reset.ts"
Cohesion: 0.07
Nodes (61): ask(), main(), rl, errorResponse(), okResponse(), POST(), ResetBody, ResetStep (+53 more)

### Community 36 - "uks.rs"
Cohesion: 0.06
Nodes (57): DesktopLoginResult, DesktopRuntimeStatus, DesktopSession, OperatorUser, SessionMode, Offline, Online, adopt_visit() (+49 more)

### Community 37 - "scanner.rs"
Cohesion: 0.07
Nodes (53): AttendanceState, Backup, current_jakarta_moment(), decision_log(), describe_addresses(), detect_device_ip_addresses(), distance_meters(), Employee (+45 more)

### Community 38 - "class_attendance.rs"
Cohesion: 0.06
Nodes (50): assert_unit_exists(), atur_jam_selesai_bel(), atur_nomor_jam_bel(), BOLOS_BAWAAN, class_status(), configured_jp_max(), dasar(), DEFAULT_JP_DURATION_MINUTES (+42 more)

### Community 39 - "time_policy.rs"
Cohesion: 0.07
Nodes (59): add_days(), alfa_generation_minute(), batas_pulang_tidak_memperpanjang_hari_shift_fleksibel(), calculate_normal_work_minutes(), calculate_work(), calculate_work_on_timeline(), check_in_minute_on_shift_timeline(), checkout_without_entry_needs_verification() (+51 more)

### Community 40 - "inventory.rs"
Cohesion: 0.03
Nodes (50): ALASAN_FORMULIR, ALASAN_MUTASI, ascii_lower(), AturanUnit, build_cancellation(), build_cancellation_swaps_sides(), cancellation_id(), CLOUD_INSERT_MUTATION_SQL (+42 more)

### Community 41 - "administration.rs"
Cohesion: 0.08
Nodes (57): attendance_events(), attendance_json(), clean_time(), clock_duration(), create_backup(), create_backup_and_correction_workflow_in_rust(), create_correction(), dashboard_data() (+49 more)

### Community 42 - "payroll-recap.ts"
Cohesion: 0.06
Nodes (55): pinjamanAktif(), applyOvertimePolicy(), BpjsBreakdownEntry, BpjsRule, calculateBpjs(), calculateComponents(), calculateOvertimeIndex(), calculatePph21Ter() (+47 more)

### Community 43 - "UksWorkspace.tsx"
Cohesion: 0.07
Nodes (55): BarisObat(), BarisObatState, Feedback, FormBuka(), FormSimpan(), galatDenganSinkron(), jamSekarangWib(), KELUHAN_UMUM (+47 more)

### Community 44 - "scanner/page.tsx"
Cohesion: 0.07
Nodes (50): @tauri-apps/api, @vladmandic/human, ScanLogItem, ScannerPage(), BulkEnrollModal(), CameraEnrollModal(), Filter, jenisLabel() (+42 more)

### Community 45 - "grades.rs"
Cohesion: 0.07
Nodes (40): delete_frozen_ledger(), float(), freeze_attendance_ledger(), get_frozen_ledger(), get_ledger_preview(), integer(), new_ledger_id(), _optional_text() (+32 more)

### Community 46 - "desktop-session-store.ts"
Cohesion: 0.06
Nodes (43): metadata, RootLayout(), DesktopLoginResponse, DesktopSessionMode, DesktopSessionSnapshot, emit(), getDesktopSessionServerSnapshot(), getDesktopSessionSnapshot() (+35 more)

### Community 47 - "rapel.rs"
Cohesion: 0.06
Nodes (48): BarisSlip, BATAL_RAPEL_SQL, bulan_ke(), bulat(), CALC_TYPE_RAPEL, calon(), cancel(), CLOUD_CANCEL_RAPEL_SQL (+40 more)

### Community 48 - "wa_notification.rs"
Cohesion: 0.05
Nodes (49): ambang_alfa_diurai_sesuai_vektor_typescript(), cerminan_lokal_langsung_terbaca_scanner(), clamp_ambang_alfa_days(), clamp_ambang_alfa_limit(), clamp_pengingat_hari_lewat(), clamp_pengingat_hari_sebelum(), compose_from_stored(), DEFAULT_AMBANG_ALFA_DAYS (+41 more)

### Community 49 - "dashboard/page.tsx"
Cohesion: 0.08
Nodes (43): clsx, motion, tailwind-merge, DashboardPage(), loadOverviewData(), formatDisplayDateTime(), formatMinutesToHours(), formatTimeOnly() (+35 more)

### Community 50 - "db-migrations.ts"
Cohesion: 0.08
Nodes (41): AccessSubject, base64ToBytes(), bytesToBase64(), constantTimeEqual(), derivePassword(), hashPasswordValue(), hashVerifiedPasswordForUpgrade(), verifyPassword() (+33 more)

### Community 51 - "two-factor/route.ts"
Cohesion: 0.09
Nodes (46): Manajemen Sekolah - Core Engineering Rules, This is NOT the Next.js you know, assertPasswordSaatIni(), POST(), runtime, TwoFactorBody, TwoFactorStep, buildOtpAuthUri() (+38 more)

### Community 52 - "attendance-processor.ts"
Cohesion: 0.09
Nodes (46): ExplicitInstant, formatJamOperasional(), formatTimestampOperasional(), ATTENDANCE_SOURCE_VALUES, AttendanceSource, DEFAULT_ATTENDANCE_SOURCE, PERSONNEL_ROLES, PersonnelRole (+38 more)

### Community 53 - "server/license.ts"
Cohesion: 0.09
Nodes (44): bodySchema, POST(), runtime, bodySchema, POST(), runtime, POST(), runtime (+36 more)

### Community 54 - "services/loan.ts"
Cohesion: 0.09
Nodes (46): BarisTulis, barisDua(), catatMutasiTx(), catatPembayaranPayrollTx(), decideLoan(), deferLoan(), Executor, hariIni() (+38 more)

### Community 55 - "hari-kerja.ts"
Cohesion: 0.08
Nodes (40): ambilDetail(), angka(), eksporLaporanKehadiran(), teks(), LABEL_JENIS, LiburMassalDialog(), Tab, tanggalPanjang() (+32 more)

### Community 56 - "services/tutup-buku.ts"
Cohesion: 0.11
Nodes (43): BarisRiwayat(), kodePendek(), RingkasVersi(), trialBalance(), assertPeriodeTerbuka(), bacaTutup(), barisTutup(), batasTutup() (+35 more)

### Community 57 - "request-security.ts"
Cohesion: 0.06
Nodes (31): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+23 more)

### Community 58 - "login/route.ts"
Cohesion: 0.11
Nodes (31): errorResponse(), LoginBody, POST(), runtime, DELETE(), noStoreJson(), POST(), runtime (+23 more)

### Community 59 - ".ensure_schema"
Cohesion: 0.09
Nodes (30): antrean_wa_cloud_menolak_dedupe_ganda_lintas_perangkat(), apply_event_to_turso(), bootstrap_lalu_login_berhasil_tanpa_jaringan(), BootstrapStatus, BootstrapSuperadminDraft, DatabaseConfigView, insert_log_if_missing(), insert_payroll_audit_log() (+22 more)

### Community 60 - "license.rs"
Cohesion: 0.05
Nodes (31): android_id(), BUILD_DATE, DEVICE, device_code(), device_code_is_stable_and_well_formed(), grant_allows(), hardware_id(), INSTANCE (+23 more)

### Community 61 - "siswa_dapodik.rs"
Cohesion: 0.07
Nodes (40): AGAMA, ALAT_TRANSPORTASI, Aturan, Angka, Digit, Email, Hp, Pilihan (+32 more)

### Community 62 - "shifts/route.ts"
Cohesion: 0.09
Nodes (36): DELETE(), OperatorMutationBody, parseDraft(), PATCH(), POST(), prepareMutation(), runtime, DELETE() (+28 more)

### Community 63 - "content-admin.ts"
Cohesion: 0.09
Nodes (34): buatIdBerita(), ContentNotFoundError, ContentValidationError, deleteArticle(), getArticle(), getArticleBySlug(), getPageContent(), saveArticle() (+26 more)

### Community 64 - "face_match.rs"
Cohesion: 0.09
Nodes (35): a(), b(), c(), cloud_template_values(), CLOUD_UPSERT_TEMPLATE_SQL, decode_face_vector(), FACE_MODEL_ID, face_settings() (+27 more)

### Community 65 - "akademik/page.tsx"
Cohesion: 0.11
Nodes (34): AkademikPage(), JadwalPanel, JamPelajaranCard, JurusanPanel, MapelPanel, ModalKey, PenugasanPanel, RombelPanel (+26 more)

### Community 66 - "time-policy.ts"
Cohesion: 0.09
Nodes (37): addCalendarDays(), assertNonNegativeInteger(), assertPolicyMinutes(), AturanJamKerja, AturanJendelaMasuk, AturanShiftDariJam, calendarDayDifference(), DecideTimeScanInput (+29 more)

### Community 67 - "secrets.rs"
Cohesion: 0.13
Nodes (31): OfflineCredential, CLIENT_ID, corrupted_salt_is_rejected_without_trusting_the_snapshot(), CREDENTIAL_KEY, credential_paths(), derive_key(), derive_turso_key(), device_id() (+23 more)

### Community 68 - "storage.rs"
Cohesion: 0.13
Nodes (37): ATTENDANCE_SOURCE_VALUES, audit(), clear_login_failures(), CLOUD_MIRRORED_TABLES, database(), DATABASE_NAME, device_identity_is_local_and_stable(), DEVICE_OWNED_TABLES (+29 more)

### Community 69 - "services/payroll-rapel.ts"
Cohesion: 0.11
Nodes (33): BarisSlip, calon(), cancelRapel(), detectRapel(), Executor, keBarisSlip(), listRapel(), saveRapel() (+25 more)

### Community 70 - "saveFileWithPicker"
Cohesion: 0.12
Nodes (32): Baris, DataDapodikDetail(), Kelompok(), TombolEksporDapodik(), ekspor(), TombolEksporDapodikSiswa(), ekspor(), dataUrlToBlob() (+24 more)

### Community 71 - "face-match.ts"
Cohesion: 0.09
Nodes (31): KeamananAbsensiCardProps, decodeFaceVector(), FACE_MODEL_ID, FACE_MODES, FACE_TEMPLATE_MAX_SAMPLES, FACE_TEMPLATE_SOURCES, FACE_THRESHOLD_DEFAULT, FACE_THRESHOLD_MAX (+23 more)

### Community 72 - "services/nilai-akhir.ts"
Cohesion: 0.12
Nodes (36): getLedgerPreview(), BarisJenis, bobotKehadiran(), config(), deleteType(), duaDesimal(), erapor(), Executor (+28 more)

### Community 73 - "api-response.ts"
Cohesion: 0.08
Nodes (25): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+17 more)

### Community 74 - "services/counseling.ts"
Cohesion: 0.10
Nodes (27): POST(), runtime, POST(), runtime, POST(), runtime, POST(), runtime (+19 more)

### Community 75 - "id-cards/page.tsx"
Cohesion: 0.11
Nodes (29): ActiveTab, BuilderPanel, DEFAULT_ID_CARD_ELEMENTS, IdCardsPage(), LayoutPanel, CollectionRepeater(), CollectionRepeaterProps, FieldKoleksi (+21 more)

### Community 76 - "fixture"
Cohesion: 0.15
Nodes (36): aktifkan(), attendance_log_and_outbox_are_rolled_back_together(), daftar_ip_kosong_tidak_membatasi_scan(), daftar_ip_terisi_menolak_alamat_di_luar_daftar(), desktop_geofence_rejection_is_logged_without_attendance(), duplicate_is_logged_without_changing_daily_attendance(), ejaan_jenis_personil_huruf_besar_tetap_dikenali_sebagai_siswa(), fitur_foto_mati_membuat_sakelar_role_tidak_berlaku() (+28 more)

### Community 77 - "setup_state"
Cohesion: 0.14
Nodes (34): automatic_codes_are_sequential_per_prefix(), cancellation_is_idempotent_and_guards_consumed_stock(), decimal_items_lock_after_history_and_round_procurement_value(), document(), document_groups_by_number_and_skips_cancelled_rows(), duplicate_codes_from_offline_devices_are_flagged(), expirable_batches_follow_their_own_id(), expirable_return_goes_back_to_its_batch() (+26 more)

### Community 78 - "portability.rs"
Cohesion: 0.09
Nodes (21): backup_file_name(), BACKUP_MAGIC, berkas_terenkripsi_bolak_balik_utuh(), buat_hub(), database_asing_ditolak_sebelum_menimpa_apa_pun(), decrypt_backup(), derive_backup_key(), encrypt_backup() (+13 more)

### Community 79 - "sql_backend.rs"
Cohesion: 0.13
Nodes (18): bind_arguments(), boolean_tersimpan_sebagai_integer(), decode_hrana_cell(), decode_local_cell(), integer_besar_tidak_kehilangan_presisi(), kolom_dan_baris_terbaca_sesuai_urutan(), LOCAL_PRAGMAS, LocalTransport (+10 more)

### Community 80 - "operators/page.tsx"
Cohesion: 0.14
Nodes (30): ActiveTab, EDITABLE_PERMISSION_GROUPS, EMPTY_OPERATOR, errorMessage(), FormField(), MasterOperatorPage(), ModalActions(), OperatorFormModal() (+22 more)

### Community 81 - "services/correction.ts"
Cohesion: 0.14
Nodes (28): formatDateTime(), LogRemoval, rebuildAttendanceFromLogs(), RebuildResult, SqlExecutor, aturanShiftDariBaris(), diDalamJendelaScanMasuk(), diDalamRentangKoreksiMasuk() (+20 more)

### Community 82 - "MailSettingsCard.tsx"
Cohesion: 0.15
Nodes (27): MailSettingsCard(), getMailConfig(), JsonRecord, MailTestResult, normalizeConfig(), record(), saveMailConfig(), sendTestMail() (+19 more)

### Community 83 - "csp"
Cohesion: 0.06
Nodes (31): debugApplicationIdSuffix, app, security, windows, build, beforeBuildCommand, beforeDevCommand, devUrl (+23 more)

### Community 84 - "erapor.ts"
Cohesion: 0.13
Nodes (28): bacaPemetaan(), DialogErapor(), ekspor(), ubahPemetaan(), EksporErapor(), namaBerkas(), pemetaanSah(), simpanPemetaan() (+20 more)

### Community 85 - "gateways/grades.ts"
Cohesion: 0.14
Nodes (27): DialogJenis(), jalankan(), NAMA_HARI, PanelBobot(), simpan(), PanelHariSekolah(), simpan(), PengaturanNilai() (+19 more)

### Community 86 - "berkas_sekolah.rs"
Cohesion: 0.11
Nodes (27): ambil_berkas_siswa(), batas_ukuran_dihitung_dari_isi(), BerkasSah, daftar_berkas_siswa(), galat_validasi(), hapus_berkas_pmb(), hapus_berkas_siswa(), id_berkas() (+19 more)

### Community 87 - "TursoConfig"
Cohesion: 0.11
Nodes (17): turso_endpoint_normalization(), auth_token_is_optional_only_where_it_is_safe(), DatabaseProvider, LocalFile, SelfHosted, Turso, insecure_flag_is_dropped_outside_self_hosted_mode(), is_private_network_host() (+9 more)

### Community 88 - "KasbonWorkspace.tsx"
Cohesion: 0.17
Nodes (25): bacaNominal(), bulanIni(), DialogDetail(), jalankan(), DialogPengajuan(), simpan(), Feedback, Filter (+17 more)

### Community 89 - "wa_sender.rs"
Cohesion: 0.13
Nodes (18): config(), drain(), fonnte_rejection(), int(), keputusan_baris_antrean(), permintaan_per_provider(), provider_request(), ProviderRequest (+10 more)

### Community 90 - "TutupBukuPanel.tsx"
Cohesion: 0.15
Nodes (21): hariIniWib(), INPUT, LABEL, TOMBOL_BAHAYA, TOMBOL_KEDUA, TOMBOL_UTAMA, BarisKolom(), DialogKolomTambahan() (+13 more)

### Community 91 - "validations/nilai-akhir.ts"
Cohesion: 0.11
Nodes (24): kehadiranSiswa(), skalaSeratus(), BATAS_PENILAIAN_REKAP, bulatAkhir(), hadirDiGerbang(), HARI_SEKOLAH_BAWAAN, hariSekolahUntuk(), hitungNilaiAkhir() (+16 more)

### Community 92 - "attendance_dashboard.rs"
Cohesion: 0.12
Nodes (21): baca_statistik(), dasbor_kosong_tetap_berhasil(), db_error(), GATE_SUMMARY_SUBQUERY, get_attendance_dashboard_metrics(), KelompokPersonil, GuruPtk, Siswa (+13 more)

### Community 93 - "scripts"
Cohesion: 0.07
Nodes (27): scripts, bootstrap:superadmin, build, build:desktop, build:web, check, check:quick, dev (+19 more)

### Community 94 - "database-config.ts"
Cohesion: 0.11
Nodes (20): client, config, email, name, noHp, password, username, noStoreJson() (+12 more)

### Community 95 - "gateways/password-reset-history.ts"
Cohesion: 0.14
Nodes (24): approvePasswordReset(), getPasswordResetHistory(), getPasswordResetPhoto(), getPasswordResetRoute(), JsonRecord, normalizeEntry(), record(), ResetApprovalResult (+16 more)

### Community 96 - "konten_gambar.rs"
Cohesion: 0.10
Nodes (18): ambil(), GambarTerurai, HAPUS_GAMBAR_YATIM_SQL, id_gambar_konten(), id_gambar_konten_sah(), JENIS_GAMBAR_KONTEN, JPEG, MAKS_BYTE_GAMBAR_KONTEN (+10 more)

### Community 97 - "wa-sender.ts"
Cohesion: 0.12
Nodes (24): discounts(), hariIni(), list(), master(), remind(), remindAuto(), siswaMenunggak(), text() (+16 more)

### Community 98 - "validate_mutation"
Cohesion: 0.11
Nodes (26): alasan_sah_untuk(), ASET, BarangDraft, BarangInfo, BarangValid, clean(), clean_tempat(), draft() (+18 more)

### Community 99 - "package.json"
Cohesion: 0.08
Nodes (24): engines, bun, node, name, overrides, nanoid, packageManager, private (+16 more)

### Community 100 - "visual-store.ts"
Cohesion: 0.16
Nodes (20): AnimatedCounter(), AnimatedCounterProps, numberFormat, render(), AuroraBackground(), AdaptiveQuality(), OPTIONS, TIER_LABEL (+12 more)

### Community 101 - "invalid"
Cohesion: 0.19
Nodes (23): assert_saldo_cukup(), barang_dilacak(), buat_unit(), cancel_mutation(), canonical_option(), canonical_tempat(), enqueue_mutasi(), insert_mutasi() (+15 more)

### Community 102 - "Value"
Cohesion: 0.18
Nodes (17): apply_snapshot_with_pulse(), apply_table(), apply_tombstones(), attendance_row(), enqueue_employee_snapshot(), entity_key(), guard_key(), is_device_local_setting() (+9 more)

### Community 103 - "LabelQr.tsx"
Cohesion: 0.16
Nodes (19): @zxing/browser, cetakBeritaAcara(), cetakLabelBarang(), esc(), isi(), kop(), LABEL_PER_LEMBAR, selisih() (+11 more)

### Community 104 - "DeviceProfileCard.tsx"
Cohesion: 0.15
Nodes (20): explainTier(), TIER_LABEL, TIER_TONE, VisualState, DeviceProfile, DeviceProfileEntry, NavigatorWithUaData, prefersReducedMotion() (+12 more)

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
Cohesion: 0.21
Nodes (18): assertNoDuplicate(), HolidayWhitelistInput, newWhitelistId(), normalizeInput(), rowToEntry(), tambahHolidayWhitelist(), updateHolidayWhitelist(), evaluateHolidayScan() (+10 more)

### Community 109 - "queue_wali_notification_tx"
Cohesion: 0.15
Nodes (18): compose_wa_message(), is_valid_phone(), new_wa_notification_id(), normalize_phone_canonical(), notifikasi_wali_dedupe_sekali_saja(), notifikasi_wali_hanya_untuk_siswa(), notifikasi_wali_menghormati_sakelar(), nyalakan() (+10 more)

### Community 110 - "config.rs"
Cohesion: 0.12
Nodes (9): BUILD_OFFLINE_MAX_AGE_HOURS, BUILD_TURSO_AUTH_TOKEN, BUILD_TURSO_DATABASE_URL, DESKTOP_HTTP_TIMEOUT_SECONDS, parse_bool_setting(), parse_offline_hours(), parse_offline_hours_value(), parse_provider_setting() (+1 more)

### Community 111 - "AttendanceGauge3D.tsx"
Cohesion: 0.16
Nodes (18): @react-three/fiber, three, AttendanceGauge3D(), AttendanceGauge3DProps, CHART_VARS, readChartPalette(), RingSegment(), Scene() (+10 more)

### Community 112 - "isMobileRuntime"
Cohesion: 0.21
Nodes (17): DatabaseBackupCard(), formatSize(), normalizeWhatsAppNumber(), openExternalUrl(), openPhoneDialer(), openWhatsAppChat(), assertTauriRuntime(), DataFolderInfo (+9 more)

### Community 113 - "PayrollCalculator"
Cohesion: 0.15
Nodes (5): dasar_negatif_tidak_pernah_mengurangi_tunjangan(), jenis_perhitungan_komponen_dihitung_dari_dasar_masing_masing(), normalize_personnel_role(), PayrollCalculator, upah_dari_menit_membulatkan_titik_tengah_menjauhi_nol()

### Community 114 - "ip-allowlist.ts"
Cohesion: 0.23
Nodes (17): RFC-5952, formatIpAddress(), formatIpv4(), formatIpv6(), ipMatchesAllowlist(), matchesEntry(), MAX_IP_ALLOWLIST_ENTRIES, normalizeIpEntry() (+9 more)

### Community 115 - "services/grades.ts"
Cohesion: 0.22
Nodes (16): buatIdNilai(), deleteAssessment(), getAssessment(), GradeNotFoundError, GradeValidationError, jenisSaringan(), jenisTidakDikenal(), jenisUntukSimpan() (+8 more)

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

### Community 121 - "enforce_any"
Cohesion: 0.20
Nodes (18): bootstrap_license_text(), check_installable(), compact_license_text(), current_device_code(), enforce_any(), evaluate_text(), gate_login(), grant_from() (+10 more)

### Community 122 - "attendance-photos/query/route.ts"
Cohesion: 0.27
Nodes (14): PhotoQueryBody, POST(), runtime, ATTENDANCE_PHOTO_MAX_LIMIT, AttendancePhotoEntry, AttendancePhotoFilter, AttendancePhotoImage, attendancePhotoLimit() (+6 more)

### Community 123 - "DecisionReason"
Cohesion: 0.12
Nodes (17): rejected_decision_message(), DecisionReason, AlreadyCheckedOut, CheckoutTooLate, CheckoutWithoutEntry, EarlyCheckout, EarlyEntry, EntryWindowClosed (+9 more)

### Community 124 - "bimbingan-konseling/page.tsx"
Cohesion: 0.28
Nodes (14): BimbinganKonselingPage(), getDaftarTahunAjaran(), getCompanyProfile(), addCounselingSessionGateway(), createCounselingCaseGateway(), deleteCounselingCaseGateway(), deleteCounselingSessionGateway(), getCounselingCaseGateway() (+6 more)

### Community 125 - ".authenticate_operator"
Cohesion: 0.17
Nodes (9): chrono_like_now_iso(), generate_recovery_codes(), hash_password_pbkdf2(), hash_password_pbkdf2_with_iterations(), normalize_recovery_code(), OperatorTotp, sha256_hex(), test_pbkdf2_hash_and_verify() (+1 more)

### Community 126 - "backups/route.ts"
Cohesion: 0.25
Nodes (11): POST(), runtime, DELETE(), POST(), runtime, batalkanPenugasanBackup(), buatPenugasanBackup(), generateIdBackup() (+3 more)

### Community 127 - "landing-cms-fields.ts"
Cohesion: 0.22
Nodes (12): CmsFieldConfig, CmsSubSectionConfig, HALAMAN_CMS, ItemKoleksi, KOLEKSI_LANDING, KoleksiLandingConfig, kunciLama(), LANDING_PAGE_SUBSECTIONS (+4 more)

### Community 129 - "Evaluation"
Cohesion: 0.21
Nodes (14): device_must_be_listed(), eval(), evaluate(), Evaluation, expired_message(), grant_only_for_usable_states(), LicensePayload, LicenseStatus (+6 more)

### Community 130 - "biome.json"
Cohesion: 0.15
Nodes (12): source, assist, actions, next, react, extends, linter, domains (+4 more)

### Community 131 - "devDependencies"
Cohesion: 0.15
Nodes (13): devDependencies, babel-plugin-react-compiler, @biomejs/biome, dotenv, @playwright/test, @tauri-apps/cli, @types/bun, @types/node (+5 more)

### Community 132 - "migrate-old-db.ts"
Cohesion: 0.18
Nodes (10): migrationEventId(), migrationFailures, nowEpoch, outboxStmt, sha256(), sourceDb, sourceDbPath, tablesToMigrate (+2 more)

### Community 133 - "templates/route.ts"
Cohesion: 0.29
Nodes (9): POST(), runtime, POST(), prepare(), PUT(), runtime, DEFAULT_ID_CARD_ELEMENTS, getIdCardTemplate() (+1 more)

### Community 134 - "services/attendance-audit.ts"
Cohesion: 0.20
Nodes (11): menitPenutupanScanPulang(), auditKualitasAbsensi(), BarisAbsensi, BarisLogAudit, BarisShift, HasilAuditAbsensi, KeparahanTemuan, labelMenit() (+3 more)

### Community 135 - "database-promotion.ts"
Cohesion: 0.27
Nodes (9): assertPromotionOrder(), detectUniqueCollisions(), planIdRemap(), PROMOTION_EXCLUDED_TABLES, PROMOTION_PLAN, PromotionTable, Row, rowKey() (+1 more)

### Community 136 - "with"
Cohesion: 0.26
Nodes (11): base_payload(), device_binding_respects_mobile_flag(), evaluation_states(), parse_license(), payload_rules_match_issuer(), public_key(), sign(), twin_vectors_verify_and_parse() (+3 more)

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
Cohesion: 0.29
Nodes (7): desktop_check_bootstrap_database(), desktop_link_bootstrap_database(), desktop_test_turso_connection(), ensure_bootstrap_window_open(), mode_lokal_tidak_menuntut_alamat_saat_provisioning(), provider_remote_tetap_menuntut_alamat(), resolve_bootstrap_turso_config()

### Community 141 - "rekapPdf.ts"
Cohesion: 0.29
Nodes (5): angka(), buatRekapPdf(), InfoRekap, tanggalPendek(), RekapNilaiAkhir

### Community 142 - "detail/route.ts"
Cohesion: 0.24
Nodes (8): bodySchema, POST(), runtime, POST(), runtime, listLoans(), loanDetail(), text()

### Community 143 - "RekapNilai.tsx"
Cohesion: 0.36
Nodes (9): angka(), catatanBolos(), PropsRekap, RekapIsi(), ekspor(), unduhPdf(), RekapNilai(), tanggalPendek() (+1 more)

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
Cohesion: 0.36
Nodes (6): listRiwayatIdentitasKaryawan(), EMPLOYEE_IDENTITY_FIELDS, LABEL_IDENTITAS_KARYAWAN, normalisasiRiwayatIdentitas(), parseRingkasan(), RiwayatIdentitasKaryawan

### Community 150 - "validate_payload"
Cohesion: 0.25
Nodes (8): is_code_shape(), is_device_code(), is_instance_code(), is_license_id(), is_product_code(), is_website_host(), string_field(), validate_payload()

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

### Community 163 - "LicenseState"
Cohesion: 0.33
Nodes (6): LicenseState, Active, DeviceNotListed, Invalid, Missing, ReadOnly

### Community 164 - "backfill/route.ts"
Cohesion: 0.50
Nodes (3): POST(), runtime, backfillMissingIdCards()

### Community 165 - "delete-rate/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, deleteTarif()

### Community 166 - "save-portal/route.ts"
Cohesion: 0.50
Nodes (4): bodySchema, POST(), runtime, savePortal()

### Community 167 - "employees/query/route.ts"
Cohesion: 0.50
Nodes (4): EmployeeQueryBody, POST(), runtime, getDaftarKaryawan()

### Community 168 - "teachers/query/route.ts"
Cohesion: 0.50
Nodes (3): POST(), runtime, getTeachers()

### Community 170 - "import_payload"
Cohesion: 0.60
Nodes (5): hub_path(), import_database(), import_database_bytes(), import_payload(), ImportReport

### Community 171 - "RowAction"
Cohesion: 0.40
Nodes (5): row_action(), RowAction, CancelDisabled, CancelDuplicate, Send

### Community 172 - "build"
Cohesion: 0.40
Nodes (4): build, beforeDevCommand, devUrl, $schema

### Community 173 - "device_name"
Cohesion: 0.67
Nodes (4): android_device_label(), android_property(), device_name(), tidy_device_name()

## Knowledge Gaps
- **81 isolated node(s):** `../biome.json`, `@tailwindcss/postcss`, `postcss`, `tailwindcss`, `@biomejs/biome` (+76 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 2009 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **14 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next` connect `next` to `toApiErrorResponse`, `isDesktopRuntime`, `react`, `ApiRequestError`, `templates/route.ts`, `login/page.tsx`, `Icon`, `siswa/page.tsx`, `ref_bun_test`, `face-template/route.ts`, `ensureServerDatabaseInitialized`, `presensi-kelas/page.tsx`, `detail/route.ts`, `AttendanceGaugeGate.tsx`, `next.config.ts`, `jp/route.ts`, `authorize.ts`, `face-liveness.ts`, `attendance-photos/route.ts`, `auth/password-reset.ts`, `backfill/route.ts`, `delete-rate/route.ts`, `save-portal/route.ts`, `employees/query/route.ts`, `teachers/query/route.ts`, `scanner/page.tsx`, `desktop-session-store.ts`, `dashboard/page.tsx`, `two-factor/route.ts`, `server/license.ts`, `request-security.ts`, `login/route.ts`, `shifts/route.ts`, `akademik/page.tsx`, `api-response.ts`, `services/counseling.ts`, `id-cards/page.tsx`, `operators/page.tsx`, `database-config.ts`, `package.json`, `attendance-photos/query/route.ts`, `bimbingan-konseling/page.tsx`, `backups/route.ts`?**
  _High betweenness centrality (0.083) - this node is a cross-community bridge._
- **What connects `../biome.json`, `@tailwindcss/postcss`, `postcss` to the rest of the system?**
  _81 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `toApiErrorResponse` be split into smaller, more focused modules?**
  _Cohesion score 0.019258536188558762 - nodes in this community are weakly interconnected._
- **Why does `CommandError` connect `CommandError` to `billing.rs`, `resolve_bootstrap_turso_config`, `accounting.rs`, `academic.rs`, `turso.rs`, `TursoClient`, `operational.rs`, `nilai_akhir.rs`, `payroll/commands.rs`, `loan.rs`, `.baca_keadaan_bayar_pmb`, `assert_offline_login_allowed`, `Value`, `sync.rs`, `uks.rs`, `scanner.rs`, `class_attendance.rs`, `tutup_buku.rs`, `inventory.rs`, `administration.rs`, `import_payload`, `grades.rs`, `rapel.rs`, `baca_slip`, `wa_notification.rs`, `.fmt`, `.ensure_schema`, `license.rs`, `siswa_dapodik.rs`, `face_match.rs`, `secrets.rs`, `storage.rs`, `fixture`, `setup_state`, `portability.rs`, `sql_backend.rs`, `berkas_sekolah.rs`, `TursoConfig`, `wa_sender.rs`, `attendance_dashboard.rs`, `konten_gambar.rs`, `invalid`, `Value`, `queue_wali_notification_tx`, `config.rs`, `Value`, `save_item`, `enforce_any`, `.authenticate_operator`?**
  _High betweenness centrality (0.057) - this node is a cross-community bridge._
- **Should `CommandError` be split into smaller, more focused modules?**
  _Cohesion score 0.027602836879432623 - nodes in this community are weakly interconnected._
- **Why does `react` connect `react` to `isDesktopRuntime`, `login/page.tsx`, `Icon`, `siswa/page.tsx`, `pesanGalat`, `presensi-kelas/page.tsx`, `RekapNilai.tsx`, `AttendanceGaugeGate.tsx`, `DapodikSiswa.tsx`, `InventarisWorkspace.tsx`, `pmb-admin.ts`, `services/wa-notification.ts`, `face-liveness.ts`, `KeuanganWorkspace.tsx`, `id-card-renderer.ts`, `UksWorkspace.tsx`, `scanner/page.tsx`, `desktop-session-store.ts`, `dashboard/page.tsx`, `hari-kerja.ts`, `akademik/page.tsx`, `saveFileWithPicker`, `id-cards/page.tsx`, `operators/page.tsx`, `MailSettingsCard.tsx`, `erapor.ts`, `gateways/grades.ts`, `KasbonWorkspace.tsx`, `TutupBukuPanel.tsx`, `package.json`, `visual-store.ts`, `LabelQr.tsx`, `DeviceProfileCard.tsx`, `AttendanceGauge3D.tsx`, `isMobileRuntime`, `bimbingan-konseling/page.tsx`?**
  _High betweenness centrality (0.028) - this node is a cross-community bridge._
- **Should `isDesktopRuntime` be split into smaller, more focused modules?**
  _Cohesion score 0.02839250972762646 - nodes in this community are weakly interconnected._