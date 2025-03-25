# GeoByte - Classroom Attendance Marking System

GeoByte is a location-based, biometric attendance management system designed for educational institutions. The app ensures authentic attendance tracking through multiple verification layers including geofencing, biometric authentication, and other security measures.

## Features

### For Students
1. **Authentication**
   - Login with institutional email (@iiitdwd.ac.in)
   - Email verification through OTP
   - Select class/section during registration

2. **Attendance Marking**
   - View active classes in real-time
   - Multi-layer verification:
     - Location verification (must be inside classroom)
     - Biometric authentication (Face ID/Fingerprint)
   - View attendance history
   - Check current class status

### For Faculty
1. **Class Management**
   - Create new courses
   - Start/Stop classes
   - Enable/Disable attendance
   - View real-time attendance stats
   - Manual attendance marking option

2. **Attendance Monitoring**
   - Real-time attendance tracking
   - Export attendance reports (CSV)
   - View attendance statistics
   - Proxy attempt detection
   - Manual verification of proxy cases

3. **Reports & Analytics**
   - Generate attendance reports
   - View class-wise statistics
   - Download consolidated reports
   - Track attendance patterns

## How It Works

### Student Flow
1. **Login/Registration**
   ```
   Login Selection → Student Registration → Email Verification → Dashboard
   ```

2. **Marking Attendance**
   ```
   Active Class → Location Check → WiFi Verification → Biometric Auth → Attendance Marked
   ```

### Faculty Flow
1. **Class Management**
   ```
   Create Course → Start Class → Enable Attendance → Monitor → End Class
   ```

2. **Attendance Management**
   ```
   View Attendance → Manual Marking → Export Reports → Review Proxy Cases
   ```

## Security Features

- Geofencing for location verification
- Biometric authentication
- One device, one attendance policy
- Proxy attempt detection and logging
- Faculty verification for proxy cases

## Technical Implementation

### Location Verification
- Uses device GPS
- Geofence boundary checking
- WiFi network verification (optional)

### Attendance Verification
- Face ID/Touch ID integration
- Timestamp validation
- Multiple attendance prevention

### Data Management
- Real-time attendance tracking
- Secure data storage with Appwrite
- Automated report generation
- Proxy detection system

## Usage Requirements

### For Students
- Institution email (@iiitdwd.ac.in)
- Device with biometric capability
- Location services enabled
- Internet connectivity

### For Faculty
- Faculty credentials
- Access to attendance management
- Authority to verify proxy cases

## Anti-Proxy Measures

1. **Location Verification**
   - Must be within classroom boundaries
   - GPS location tracking
   - Optional WiFi verification

2. **Biometric Authentication**
   - Face ID/Fingerprint verification
   - Real-time presence verification
   - Multiple verification attempts tracking

## Reports and Analytics

1. **Daily Reports**
   - Present/Absent lists
   - Time-stamped attendance

2. **Consolidated Reports**
   - Class-wise attendance
   - Student-wise attendance
   - Monthly/Semester reports

3. **Proxy Analysis**
   - Suspicious activity logs
   - Location verification failures

## Support

For technical support or queries:
- Contact system administrator
- Report issues through the faculty dashboard
- Email support team for assistance

