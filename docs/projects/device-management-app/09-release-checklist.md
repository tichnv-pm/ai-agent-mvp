> Template này dùng bởi PM Agent. Không sửa trực tiếp khi tạo dự án mới. Hãy copy sang `docs/projects/<project-folder>/` rồi điền thông tin dự án.

# 09-release-checklist.md

App quản lý thiết bị cho một công ty phần mềm
[CÀN XÁC NHẬN: project-code]
[CÀN XÁC NHẬN: project-manager]
[CÀN XÁC NHẬN: project-manager]
[CÀN XÁC NHẬN: customer]
[CÀN XÁC NHẬN: start-date]
[CÀN XÁC NHẬN: start-date]

## Phạm vi release
Release v1.0 - Core functionality

### Checklist nghiệp vụ
- [ ] Thêm thiết bị thành công
- [ ] Phân công thiết bị
- [ ] Ghi chép bảo trì
- [ ] Báo cáo thiết bị
- [ ] Thông báo hết hạn bảo hành
- [ ] Tích hợp với HR (tùy chọn)

### Checklist kỹ thuật
- [ ] API documentation hoàn thành
- [ ] Unit tests pass >90%
- [ ] Integration tests pass
- [ ] Security review
- [ ] Performance test
- [ ] Container image build
- [ ] Deploy to staging
- [ ] Smoke test

### Checklist test
- [ ] Manual test user journey
- [ ] API endpoint testing
- [ ] Data validation testing
- [ ] Error handling testing
- [ ] Permission testing
- [ ] Load testing

### Checklist dữ liệu
- [ ] Dữ liệu test được import
- [ ] Bảo vệ dữ liệu người dùng
- [ ] Backup data
- [ ] Migration script

### Checklist deployment
- [ ] Deploy to production
- [ ] Cấu hình monitoring
- [ ] Cấu hình alerting
- [ ] Cập nhật documentation

#### Rollback plan
- Rollback command: kubectl delete deployment device-management-app
- Time limit: 30 minutes
- Criteria: Nếu error rate >5% or response time >2s
- Người phụ trách: DevOps

#### Người xác nhận
- Product Owner
- IT Manager
- QA Lead

## Next actions
[CÀN XÁC NHẬN: next-actions]