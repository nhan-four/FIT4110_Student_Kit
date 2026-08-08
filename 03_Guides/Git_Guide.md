# Git guide — one semester repository

## Create the portfolio first

Before Lab 01, create one empty **public** GitHub repository: `FIT4110_<MãSinhViên>`. Clone it locally, create the lab folders below, and make an initial commit. This ensures Lab 01 evidence records your own Git history.

```text
FIT4110_<MãSinhViên>/
├── 01_Setup/
├── 02_OpenAPI/
├── 03_Postman/
├── 04_Docker/
├── 05_Compose/
└── 06_Plugathon/
```

Set `origin` once, when creating the portfolio: `https://github.com/<your-account>/FIT4110_<MãSinhViên>.git`.

## Move a completed lab into the portfolio

1. Clone the source starter separately and complete the lab there.
2. Remove only the starter's `.git` directory; do not copy a Git repository inside your portfolio.
3. Copy the completed files into the matching portfolio folder. For Lab 01, run evidence collection from `01_Setup/` after copying.
4. Do not rely on source GitHub Actions. Workflows under `02_OpenAPI/.github/workflows/` or another lab folder are not recognised by GitHub, and source workflows assume that their lab files are at the repository root.
5. Run the stated commands locally and keep reports/evidence in the lab folder.

From the portfolio root:

```bash
git status
git add 03_Postman
git commit -m "lab03: add contract tests and evidence"
git push -u origin main
```

Use small, meaningful commits. Do not commit `.env`, tokens, private datasets, or generated dependency folders. After a lab deadline, preserve history and document any correction in a new commit.

---

## Bản tiếng Việt

# Git guide — một repository cho cả học kỳ

## Tạo portfolio trước

Trước Lab 01, tạo một GitHub repository **public** rỗng: `FIT4110_<MãSinhViên>`. Clone repository này về máy, tạo các thư mục Lab dưới đây và tạo commit đầu tiên. Việc này bảo đảm minh chứng Lab 01 ghi lại Git history của chính sinh viên.

```text
FIT4110_<MãSinhViên>/
├── 01_Setup/
├── 02_OpenAPI/
├── 03_Postman/
├── 04_Docker/
├── 05_Compose/
└── 06_Plugathon/
```

Chỉ đặt `origin` một lần khi tạo portfolio: `https://github.com/<your-account>/FIT4110_<MãSinhViên>.git`.

## Đưa một Lab đã hoàn thành vào portfolio

1. Clone riêng starter nguồn và hoàn thành Lab tại đó.
2. Chỉ bỏ thư mục `.git` của starter; không sao chép Git repository vào bên trong portfolio.
3. Sao chép các file đã hoàn thành vào thư mục Lab tương ứng trong portfolio. Với Lab 01, chạy evidence collection từ `01_Setup/` sau khi sao chép.
4. Không dựa vào GitHub Actions của starter. Workflow nằm dưới `02_OpenAPI/.github/workflows/` hoặc thư mục Lab khác sẽ không được GitHub nhận diện; workflow nguồn cũng giả định file của Lab nằm tại root repository.
5. Chạy các lệnh được yêu cầu tại local và lưu report/minh chứng trong thư mục Lab.

Từ root của portfolio:

```bash
git status
git add 03_Postman
git commit -m "lab03: add contract tests and evidence"
git push -u origin main
```

Dùng commit nhỏ, có ý nghĩa. Không commit `.env`, token, dữ liệu riêng tư hoặc thư mục dependency được sinh tự động. Sau mốc nộp Lab, giữ nguyên lịch sử và ghi lại mọi sửa đổi bằng commit mới.
